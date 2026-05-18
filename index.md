---
layout: default
title: Home
---

<link rel="stylesheet" href="{{ '/assets/css/home.css' | relative_url }}">

<section class="hero">
  <div class="hero__content">
    <p class="eyebrow">Software Developer</p>
    <h1>Duncan Campbell</h1>
    <p class="hero__intro">
      Nerding it up since 2001
    </p>
    <div class="hero__actions">
      <a class="button button--primary" href="{{ '/about/' | relative_url }}">About Me</a>
    </div>
  </div>
  <aside class="hero__card" aria-labelledby="current-focus">
    <span class="status-dot"></span>
    <p class="card-label" id="current-focus">Currently focused on</p>
    <ul class="focus-list">
      <li>
        <span>Building my mum an agentic book writing tool</span>
        <a href="{{ '/blog/agentic-book-writing-tool/' | relative_url }}">Read about the tool</a>
      </li>
      <li>
        <span>Working with big data for the police</span>
        <a href="{{ '/blog/big-data-police-work/' | relative_url }}">Read about the work</a>
      </li>
    </ul>
  </aside>
</section>

<section id="writing" class="section writing-section">
  <div class="section__header">
    <p class="eyebrow">Writing</p>
    <h2>Recent Posts</h2>
  </div>

  {% if site.posts.size > 0 %}
    <div class="post-list-custom">
      {% for post in site.posts limit:3 %}
        <article class="post-card">
          <p class="post-card__date">{{ post.date | date: "%b %-d, %Y" }}</p>
          <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
          {% if post.excerpt %}
            <p>{{ post.excerpt | strip_html | truncate: 150 }}</p>
          {% endif %}
        </article>
      {% endfor %}
    </div>
  {% else %}
    <p>No posts yet. Check back soon.</p>
  {% endif %}
</section>

<section class="cta-section">
  <p class="eyebrow">Let's Connect</p>
  <h2>Interested in my work?</h2>
  <p>I have no social media because it rots your brain but if you are interested in my professional work you can contact me through my wonderful employer <a href="https://sourcelabs.nl/">sourcelabs.nl</a></p>
</section>

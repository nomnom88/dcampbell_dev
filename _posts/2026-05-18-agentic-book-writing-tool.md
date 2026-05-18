---
layout: post
title: "Building an Agentic Book Writing Tool"
date: 2026-05-18 00:02:00 +0200
categories: blog
permalink: /blog/agentic-book-writing-tool/
---

About a decade ago when my mum retired she fulfilled a lifelong dream of hers.

She wrote a book which you can buy [here](https://us.amazon.com/Harbour-Cities-Midland-Sylvia-Lowik/dp/9090353143/?_encoding=UTF8).

Then a few years later in 2022 she suffered a fall and received a traumatic brain injury that left her with aphasia.

She made it out of the coma. And slowly she began the process of being able to speak again. However a lot of words are mixed up, sometimes she says "meisje" but she means "jongen", and often that word or name is just on the tip of her tongue but she can't quite get to it.

Her dream of being a fantasy author was over. She couldn't type and she has trouble reading text.

But then around 2023-2026 the world changed.

And I feel foolish and stupid that it took me this long to realise it but in the start of 2026 I realised I could use my 20 years of being 1337 H4X0r and the miracle of agentic AI programming tools to breathe new life into that dream of hers.

Together with my brother over the last few weeks and during our last weekend hackathon at mum'n'dad's we have created a book writing companion application.

Some of the features:

- Ingestion of the *canon books* (just the one in this case) which are essentially prequels that set up lore and the world in which subsequent text should be set.
- Conversation with STT -> LLM -> TTS using FasterWhisper and Kokoro for natural sounding voices which are free and fast (enough) to run locally.
- Tooling available to the LLM to allow it to "read" text and text summaries, to search for keywords and to make edits to the new manuscript being written.
- We also offer the LLM the "tool" of being able to propose changes to the user, which our application presents as diffs a la code PRs to be accepted or declined.
- Accessibility to the max: click the "read aloud" button and any piece of text, be it a button or a label or a dropdown or whatever, will be read out for you.
- Karaoke: mum can read if she hears the words too and if the text being read is highlighted. This is available for any large text field and standard for all chat interaction.

There's a whole bunch more and when I'm happy with the level of quality of the application I will show it off properly.

And then, it's Augmented Reality time.

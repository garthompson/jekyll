---
title: "Creating a Jekyll stie"
date: 2025-08-15
excerpt_separator: "<!--more-->"
categories:
  - blog
tags:
  - Jekyll
---
For my first post on my new github-pages hosted, Jekyll-powered site, it makes sense to talk about
why and how I created it.

I played around with Jekyll years briefly years ago, and it seemed great for what it does. The fact
that a Jekyll site can be hosted free on Github also helps :wink:. To be honest, anything I once
knew about it I'd forgotten however.

Fast forward to recently where I was trying out Copilot chat. I don't know what made me think of it
but creating a Jekyll site and hosting it on github-pages seemed like a pretty self-contained task
that should be well within the Copilot's capabilities. So, how did it go?

<!--more -->

Unfortunately, as with many best-laid plans, it didn't work out exactly as intended. Probably due to
my inexperience with Jekyll, I spent probably a full day overall fighting with it via Copilot to no
avail. I eventually got something up and running, but I had little confidence that it was hanging
together by anything more than a few threads!

When looking at themes, I'd come across [Minimal Mistakes][minimal-mistakes]. Looking closer at the
docs, I spotted that they have a ["remote theme starter"][mm-gh-starter]. In a few clicks and
some Github repository configuration, my site was up and running. A few quick edits of the config
and it looked reasonable. If you include the time spent writing this post, all-told it probably
took less than an hour!

If there's a moral to this story, it's that sometimes a dedicated flow that's designed well can be
hard to beat. Maybe they'll get exposed as tools in [MCP][mcp] or the like, but until then I'll be
sure to investigate old-school methods in paralell to AI.

On to the next adventure...

[minimal-mistakes]: https://mmistakes.github.io/minimal-mistakes/
[mm-gh-starter]: https://github.com/mmistakes/mm-github-pages-starter
[mcp]: https://docs.anthropic.com/en/docs/mcp

---
layout: post
title:  "Moving to Jekyll"
date:   2022-07-09 22:34:03 +0000
categories: update
---

One of my favorite ways to learn is to start with the simplest solution, and add complexity when the existing solution fails.
I started this blog as a bunch of plain old HTML files.
That worked pretty well, but I'd prefer to not have to deal with all the html boilerplate when what adds value to this blog is content, not html.

Now I'm setting up a [Jekyll](https://jekyllrb.com) Docker image, and stripping HTML tags from my old posts.
I've decided that being able to write posts in markdown is worth adding the complexity of a static site generator.
Thankfully, my initial solution was so simple, when I replaced it there was nothing to throw away other than HTML tags.

That got me to wondering: have I added complexity?
There's now a generation step that needs to occur after changes to this [source](https://github.com/ahepp/homepage).

But in some important ways, this site is now simpler.
The signal-to-noise ratio of content files is now higher.
Adding the static site generator lets me worry less about presentation, as that's handled by themes and plugins.

I'm confident that even if I need to iterate on this design down the road, all I'll lose is a couple hours spent creating this Jekyll infrastucture.
Since the amount of non-content in my source files has now decreased, I figure I'll actually save on costs vs HTML if I end up migrating to a CMS.

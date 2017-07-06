---
title: Starting a blog
date: 2017-07-05 15:56:45
highlight_menu_key: blog
timeline_icon: icon-bubble2
---
So... I finally decided to bootstrap my personal website, the idea is to build a place to share my experiences and experiments with software and electronics crafting.
<!-- more -->
This is my first blogging experience, I'm not one of that guys that usually writes down a lot of stuff on notes or diaries, but I really feel that this experiance may be interesting for the kind of person I am.

Coming from the [Ruby](https://www.ruby-lang.org/it/) ecosystem, I have way better experiance with other static site generators or blogging platforms like [Middleman](https://middlemanapp.com) and [Jekyll](https://jekyllrb.com/) but you know what? I like to try different things and technologies. Let's see how the "Hexo way of generate static sites" will drive this first blogging experience.

At the moment of writing this post I'm going to figure out how to build the first hexo theme starting from this first post. I read deeply the [Hexo documentation](https://hexo.io/docs/) that, combined with the `landscape` example theme that ships with the `hexo init` command, should be enough to understand tha basics. So consider this first post like the `Hello World` of http://bravelycoding.it.

Let's use the **excerpt** feature to build an easy to read blog timeline for the homepage by including a comment tag with the `more` keyword inside this Markdown Post Page:

```
So... I finally decided to bootstrap my personal website, the idea is to build a place to share my experiences and experiments with software and electronics crafting.
<!-- more -->
This is my first blogging experience, I'm not one of that guys that usually writes down a lot of stuff on notes or diaries, but I really feel that this experiance may be interesting for the kind of person I am.
[...]
```

In this way Hexo will consider all the content **before** the `<!-- more -->` tag as the **excerpt** (You can access it from `post.excerpt`) and all the content **after** the tag as **more** (You can access it from `post.more`). Remember that if You just want all the content of the post You can retrieve it from `post.content`.

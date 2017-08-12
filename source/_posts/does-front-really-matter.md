---
title: Does Front Really Matter?
date: 2017-07-06 14:13:46
highlight_menu_key: blog
timeline_icon: icon-bubble2
---
Let's try to use the Front to customize dynamically the look of the blog post.
<!-- more -->
I'm using it to set the **icon** that appears both in the timeline of posts and in the post page itself, here is how I'm gonna do it:

```
---
title: Front Really Matter?
date: 2017-07-06 14:13:46
timeline_icon: icon-bubble2
---
Let's try to use the Front to customize dynamically the look of the blog post.
...
```

This *front page* sets an attribute `timeline_icon` to the **post object**, so that in the *posts layout* `layout/post.pug` and *post template* `layout/_partial/post.pug` I can use it to specify the icon I want to show in the timeline:

```
li
  // [...]
  .timeline-icon.border-blue
    i(class=post.timeline_icon)
  // [...]
```
Will produce this result:

![Post Timeline Icon](/assets/images/does-front-really-matter/post-timeline-icon.png "Post Timeline Icon")

Exactly what I want, simple and stright.

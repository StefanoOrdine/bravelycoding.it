---
title: Does Front Really Matter?
date: 2017-07-06 14:13:46
highlight_menu_key: blog
timeline_icon: icon-bubble2
---
Yeah, it seems like so!
<!-- more -->
I'm using it for the moment to customize the **icon** that appears both in the timeline of posts and in the post page itself, here is how i did it:

```
---
title: Front Really Matter?
date: 2017-07-06 14:13:46
timeline_icon: icon-bubble2
---
Yeah, it seems like so!
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

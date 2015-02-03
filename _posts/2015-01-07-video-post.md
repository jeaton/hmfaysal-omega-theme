---

layout: post
type:	video
title: A Post with a Video
tags: [all posts, video]
video: https://www.youtube.com/watch?v=OXvo6ksBHnI
comments: true

---

Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).

Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:

---
title:  "Images and other embeded content"
excerpt_separator: <!--more-->
mathjax: true
layout: post
categories: media
author: maxwell

---

## Images

You can upload an image file at the `_assets` directory of the site repository and embed it at a post's source text using the code `![title](/assets/filname.jpg))`. You can take a look at the source text for this post at the `_posts` directory to review the code in action.

![The original uploader was Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons](https://upload.wikimedia.org/wikipedia/commons/f/f9/Raynor_library%2C_Marquette_University.jpg)

[Raynor library, Marquette University](https://commons.wikimedia.org/wiki/File:Raynor_library,_Marquette_University.jpg) by Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons.

<!--more-->

## Other embedded content

You can also embed a lot of other stuff, like video files from YouTube, using the `embed.html` include at the `_includes` directory of the site repository. You can take a look at the source text for this post at the `_posts` directory to review the code in action.

{% include embed.html url="https://www.youtube.com/embed/l9TuKL3uRSQ" %}

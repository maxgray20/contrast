---
title:  "Advanced markdown examples"
excerpt_separator: <!--more-->
mathjax: true
layout: post
categories: media
---

![The original uploader was Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons](https://upload.wikimedia.org/wikipedia/commons/f/f9/Raynor_library%2C_Marquette_University.jpg)

[Raynor library, Marquette University](https://commons.wikimedia.org/wiki/File:Raynor_library,_Marquette_University.jpg) by Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons.

<!--more-->

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![ReppinSconnie, CC BY-SA 3.0, via Wikimedia Commons](https://upload.wikimedia.org/wikipedia/commons/f/f5/Aitken_Reading_Room%2C_Marquette_University_Law_School.jpg)

[Aitken Reading Room, Marquette University Law School](https://commons.wikimedia.org/wiki/File:Aitken_Reading_Room,_Marquette_University_Law_School.jpg) by ReppinSconnie, CC BY-SA 3.0, via Wikimedia Commons.

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://www.youtube.com/embed/l9TuKL3uRSQ" %}

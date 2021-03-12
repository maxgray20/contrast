---
title:  "Advanced examples"
mathjax: true
layout: post
categories: media
---

![The original uploader was Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons](https://upload.wikimedia.org/wikipedia/commons/f/f9/Raynor_library%2C_Marquette_University.jpg)

## Code

Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

## Gists

With the `jekyll-gist` plugin, which is preinstalled on Github Pages, you can embed gists simply by using the `gist` command:

<script src="https://gist.github.com/5555251.js?file=gist.md"></script>

## Images

Upload an image to the *assets* folder and embed it with `![title](/assets/name.jpg))`. Keep in mind that the path needs to be adjusted if Jekyll is run inside a subfolder.

A wrapper `div` with the class `large` can be used to increase the width of an image or iframe.

![ReppinSconnie, CC BY-SA 3.0, via Wikimedia Commons](https://upload.wikimedia.org/wikipedia/commons/f/f5/Aitken_Reading_Room%2C_Marquette_University_Law_School.jpg)

[Aitken Reading Room, Marquette University Law School](https://commons.wikimedia.org/wiki/File:Aitken_Reading_Room,_Marquette_University_Law_School.jpg) by ReppinSconnie, CC BY-SA 3.0, via Wikimedia Commons.

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.

{% include embed.html url="https://youtu.be/l9TuKL3uRSQ" %}

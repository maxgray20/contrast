---
title: "Welcome to the blog"
excerpt_separator: <!--more-->
layout: post
author: maxwell
--- 

![The original uploader was Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons](https://upload.wikimedia.org/wikipedia/commons/f/f9/Raynor_library%2C_Marquette_University.jpg)

[Raynor library, Marquette University](https://commons.wikimedia.org/wiki/File:Raynor_library,_Marquette_University.jpg) by Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons.

## How it works

This course blog for English 3210 at Marquette University is a static site built using a [GitHub](https://github.com/) repository, [GitHub Pages](https://pages.github.com/), and the popular static site generator [Jekyll](https://jekyllrb.com/). Blog posts use snippets of YAML for front matter and Markdown for the body of the post. [Markdown](https://daringfireball.net/projects/markdown/) is a text-to-HTML conversion tool for web writers that allows you to write blog post text using an *easy-to-read, easy-to-write plain text format*, and then convert your text to HTML for your blog. For example, you can see the source text for this paragraph below.

```
This course blog for English 3210 at Marquette University is a static site built using
a [GitHub](https://github.com/) repository, [GitHub Pages](https://pages.github.com/),
and the popular static site generator [Jekyll](https://jekyllrb.com/). Blog posts use
snippets of YAML for front matter and Markdown for the body of the post. [Markdown]
(https://daringfireball.net/projects/markdown/) is a text-to-HTML conversion tool for
web writers that allows you to write blog post text using an *easy-to-read, easy-to-write
plain text format*, and then convert your text to HTML for your blog. For example, you
can see the source text for this paragraph below.
```

> ### Reading Markdown
> 
> Markdown's plain text format is easy to read and write. Notice how Markdown uses brackets and parentheses for creating links, and asterisks to indicate spans of emphasis.

<!--more-->

## Adding new posts

You can find the source text for this post at the file called `2021-03-15-welcome-to-the-blog.md` at the `_posts` directory of the [site repository](https://github.com/maxgray20/english-3210). To add a new post to the blog, you can add a new `.md` file at the `_posts` directory that follows the naming convention `YYYY-MM-DD-your-post-title.md` and includes the necessary front matter. You can see the pattern for the necessary front matter below.

```
---
title: "your post title"
excerpt_separator: <!--more-->
layout: post
author: your name
---
```

> ### Reading YAML
> 
> All blog post files must begin with the necessary front matter used to set the `layout` for `post`. When the `layout` is set for `post`, this specifies the file is a blog post for the site generator.

## Markdown basics

The basics of Markdown's formatting syntax are very easy to learn simply by looking at the examples of it in action at the Markdown [documentation](https://daringfireball.net/projects/markdown/basics). You can practice Markdown using the web application [Dingus](https://daringfireball.net/projects/markdown/dingus) that allows you to practice writing your own Markdown-formatted text, and then translate it to HTML live. You can also find many Markdown video tutorials online like the one below from Steve Griffith of the media and design department at Algonquin College.

{% include embed.html url="https://www.youtube.com/embed/eJojC3lSkwg" %}

---
title: "Welcome to the blog"
excerpt_separator: <!--more-->
author: maxwell
layout: post
--- 

![The original uploader was Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons](https://upload.wikimedia.org/wikipedia/commons/f/f9/Raynor_library%2C_Marquette_University.jpg)

[Raynor library, Marquette University](https://commons.wikimedia.org/wiki/File:Raynor_library,_Marquette_University.jpg) by Illwauk at English Wikipedia., CC BY 2.0, via Wikimedia Commons.

## How it works

This course blog for English 3210 at Marquette University is developed using Jekyll and GitHub Pages. [Jekyll](https://jekyllrb.com/) is a popular static site generator that transforms your plain text into static websites and blogs. It takes Markdown-format plain text and uses YAML, Liquid, HTML and CSS layouts and style sheets to create static sites. [GitHub Pages](https://pages.github.com/) is a static site hosting service that takes HTML, CSS, and JavaScript files straight from your repository at GitHub, runs the files through a build process, and publishes your repository as a static site.

**Blog posts** are written in Markdown. [Markdown](https://daringfireball.net/projects/markdown/) is a text-to-HTML conversion tool and plain text formatting syntax for web writers that allows you to write using an *easy-to-read, easy-to-write plain text format*, and then convert it to structurally valid HTML. Jekyll includes built-in support for Markdown. You can use Markdown’s formatting syntax to write Markdown-format plain text, and Jekyll will use it to create pages and posts for the blog site. Meaning you can write blog posts for the site without any HTML, CSS or other technical skills. Here is the Markdown-format plain text for this paragraph:

```
**Blog posts** are written in Markdown. [Markdown](https://daringfireball.net/projects/markdown/)
is a text-to-HTML conversion tool and plain text formatting syntax for web writers that allows you
to write using an *easy-to-read, easy-to-write plain text format*, and then convert it to structurally
valid HTML. Jekyll includes built-in support for Markdown. You can use Markdown’s formatting syntax
to write Markdown-format plain text, and Jekyll will use it to create pages and posts for your
blog site. Meaning you can write blog posts for your site without any HTML, CSS or other
technical skills.
```

> ### Reading Markdown
> 
> Markdown's plain text format is easy to read and write. In the Markdown-format plain text above you can see Markdown uses brackets and parentheses for creating links, and asterisks to indicate spans of emphasis, and double astrisks to indicate spans of strong emphasis.

<!--more-->

**Blog post files** begin with snippets of YAML front matter which is  used to set the layout or other meta data. [YAML](https://yaml.org/) is a popular data serialization standard for programming languages like Ruby. (Jekyll is written in Ruby.) tl;dr: the front matter must be the first thing in the file and must take the form of valid YAML set between triple-dashed lines. Here is a basic example for blog post files:

```
title: "your post title"
author: your_name
layout: post
```

> ### Reading YAML
> 
> Blog post files must begin with the YAML front matter above which is used to set the layout and author meta data. When the `layout` variable is set to `post`, this specifies the file should be processed by Jekyll as a blog post.

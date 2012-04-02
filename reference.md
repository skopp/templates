---
title: Open Source at sapo - template reference
permalink: reference.html
layout: default
---

# Reference #

This page provides a slightly more in-depth guide to these templates (as well as being a usage example)

## Overview ##

The template repository is organized as a standard [Jekyll][jk] deployment, with a `_config.yml` file that enables Pygments syntax highlighting and pretty urls as such:

{% highlight yaml %}
pygments: true
permalink: pretty
{% endhighlight %}

## Tree Layout ##

This is the default filesystem layout you get when you clone the `gh-pages` branch from this repository:

<pre>
_includes
    sidebar.html
_layouts
    default.html
_config.yml
README.md
reference.md
</pre>

[jk]: http://github.com/mojombo/jekyll/
---
title: Open Source at sapo - template documentation
permalink: reference.html
layout: default
---

# Overview #

The template repository is organized as a standard [Jekyll][jk] deployment, with a `_config.yml` file that enables Pygments syntax highlighting and pretty urls as such:

{% highlight yaml %}
pygments: true
permalink: pretty
{% endhighlight %}

# Tree Layout #

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
---
title: First Gist
layout: default
excerpt: Place the introducing line of text ie.) the 'lead' here ...
version: Page Template md Dtd 02-05-18 pm
navigation_weight: 8
categories: carbonfree
---
# {{ page.title }}

{{ page.excerpt }}

{% comment %}{{ page.version }}{% endcomment %}

{% include toc.md %}

## First Subtitle

Place the introducing line of text ie.) the 'tagline' here ...

## Ping Back

The internal anchor path of this page is `{{ page.path }}`.

And, the internal anchor path to the target page is `_gists/First-Gist.md`

However, the external hyperlink path for a *Ping Back* to this page is, as follows:

- [{{ page.title }}]({% link _gists/First-Gist.md %}){:title="Click to Visit the {{ page.title }} page of the Carbon Free Footprint Project at the Concept Library of the MMINAIL"}{:target="_blank"}

{{ site.url }}{{ site.baseurl }}/{{ page.path }}(.html)

And, the internal hyperlink path to the target page is:

[First-Gist]({% link _gists/First-Gist.md %})

## Last Subtitle

Place the introducing line of text ie.) the 'tagline' here ...

### Raw Code Block

```liquid
{% raw %}
Enjoy the successful output!
{% endraw %}
```

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/Shell/Source-Shell-Links.htm){:title="Click to Visit the Source Links page of the Shell Lessons Project at GitHub pages"}{:target="_blank"} page of the Shell Lessons Project. Published by © 2017 - 2018 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

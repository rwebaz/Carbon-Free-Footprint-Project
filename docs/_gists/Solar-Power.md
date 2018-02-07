---
title: Solar Power
layout: default
excerpt: Place the introducing line of text ie.) the 'lead' here ...
version: Page Template md Dtd 02-06-18 pm
navigation_weight: 8
categories: carbonfree
---
# {{ page.title }}

{{ page.excerpt }}

{% include toc.md %}

## Time Management

```liquid
{% raw %}
{% highlight html linenos %}
console.time(programTimer,"Square It Time"); 
var programTimer; {
    Execute Function Inside This Code Block
}
console.timeEnd(programTimer,"Square It Time");
{% endhighlight %}
{% endraw %}
```

## List of Git Hub Users

```liquid
{% raw %}
{% highlight html %}
{% for member in site.data.members %}
<ul>
  <li>
    <a href="https://github.com/{{ member.github }}">
      {{ member.name }}
    </a>
  </li>
</ul>
{% endfor %}
{% endhighlight %}
{% endraw %}
```

## Image Assets

```liquid
{% raw %}
{% assign image_files = site.static_files | where: "image", true %}
{% for myimage in image_files %}
  {{ myimage.path }}
{% endfor %}
Enjoy the successful output!
{% endraw %}
```

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

- The [Project Source Links](https://mminail.github.io/CFFP/Source-Carbon-Free-Links.htm){:title="Click to Visit the Source Links page of the Carbon Free Footprint Project at GitHub pages"}{:target="_blank"} page of the Carbon Free Footprint Project. Published by © 2017 - 2018 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

**Note**. This page crafted with {{ page.version }}.

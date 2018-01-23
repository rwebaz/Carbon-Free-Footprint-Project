---
title: Solar Panels
layout: default
navigation_weight: 8
---
# Solar Panels

{{ site.tagline }}

{% include toc-flammarion.md %}

## Html Code Blocks Wrapped In A Liquid Raw Statement

```html
{% raw %}
<!-- Output onclick the result of the js function -->
<form role="form">
<div class="form-group">
<label>
<input id="1" type="button" value="Click this button" />
</label>
</div>
</form>
<output>x</output>
{% endraw %}
```

```html
{% raw %}
<h4>Vertical Definiton List</h4>
<dl class="">
<dt>Data Title</dt>
<dd>Actual Data</dd>
<dd>Actual Errata</dd>
<dd><a href="#" title="Click to Visit Same" target="_self">Hyperlink to Same Page</a></dd>
</dl>
{% endraw %}
```

```html
{% raw %}
<!-- Comment out Horizontal Definition List
<h4>Horizontal Definition List</h4>
<dl class="dl-horizontal"><dt>Data Title</dt><dd>Actual Data</dd></dl> -->
<h4>Vertical Buttons</h4>
<!-- Comment out default ( medium ) renderings 
<div class="btn-group-vertical">
<button type="button" class="btn btn-default btn-lg">Default</button>
<button type="button" class="btn btn-default btn-block">Default</button>
<button type="button" class="btn btn-default btn-sm">Default</button>
<button type="button" class="btn btn-default btn-xs">Default</button>
<div /> -->
{% endraw %}
```

```html
{% raw %}
<div class="btn-group-vertical btn-group-lg">
<button type="button" class="btn btn-primary">Primary</button>
<button type="button" class="btn btn-success">Success</button>
<button type="button" class="btn btn-info">Info</button>
<button type="button" class="btn btn-warning">Warning</button>
<button type="button" class="btn btn-danger">Danger</button>
<button type="button" class="btn btn-link">Link</button>
</div>
{% endraw %}
```

```html
{% raw %}
<h4>Split Drop-down Menu</h4>
<div class="btn-group-lg">
<!-- There is no class in Bootstrap 3.3(7) to force a 'drop-up' -->
<button type="button" class="btn btn-default"><span>Landraces</span>
<button type="button" class="btn btn-default dropdown-toggle" data-toggle="dropdown">
<i class="caret" ></i>
</button>
{% endraw %}
```

```html
{% raw %}
<ul class="dropdown-menu" role="menu">
<li><a href="#">Ruderalis</a></li>
<li><a href="#">Sativa</a></li>
<li><a href="#">Indica</a></li>
<li class="divider"></li>
<li><a href="#">Learn</a></li>
</ul>
</button>
</div>
{% endraw %}
```

## Last Subtitle

Place the introducing line of text ie.) the 'tagline' here ...

```liquid
{% raw %}
Enjoy the successful output!
{% endraw %}
```

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/Social-Media/Source-Social-Media-Links.htm){:title="Click to Visit the Source Links page of the Social-Media Lessons Project at GitHub pages"}{:target="_blank"} page of the Social-Media Lessons Project. Published by © 2000 - 2018 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

---
title: Home Page
layout: default
excerpt: Shell tags and Shell statements mimic underlying Javascript methods ...
version: Index Template md Dtd 02-05-18 pm
navigation_weight: 1
categories: carbonfree
---
![Page Banner]({{ "assets/img/svg/ghp-git-hub-pages-medmjorg-carbon-free-footprint-project-flammarion-got-tree-final-banner-1050-x-173.svg" | relative_url }}){:.img}{:.img-responsive}{:.img-rounded}

# Carbon Free Footprint Project Home Page

{{ page.excerpt }}

{% comment %}{{ page.version }}{% endcomment %}

{% include toc.md %}

## Image Filters

Prepending the `path` and `file name` of an image with simply the `site.baseurl` in liquid can be achieved with the `relative_url` filter.

However, prepending the `path` and `file name` of an image with both the `site.url` and `site.baseurl` in liquid can be achieved only with the `absolute_url` filter.

## BC Northern Lights

An analysis designed to establish a **Carbon Free Footprint** when operating a BC Northern Lights Bloombox 'Full Blast' 24/7.

## Issue

The **Issue** of a successful legal argument is prefaced by a concise, to the point coin flip.

Should it be, or should it not be?

### The Socratic Method

State the issue of the problem in the form of a question ie.) How do you code this stuff?

## Rule

The rule may be split into two components ...

### Current Majority View

What is the current view as expressed by the majority of federal districts and state courts based on the common law with reference to the UCC, 2nd Restatements, etc. et al?

### The Minority View

What is the minority view as expressed by the dissent?

{% include analysis-code-live.md %}

## Conclusion

A concise conclusion wraps the argument ...

### Summation

Delineate the steps ...

### Solution

Expound the solution ...

### Gist Links

The path to this page is ... `{{ page.path }}`

The path to the target page is ...

{% for gist in site.gists %}

- [{{ gist.title }}]({{ site.url }}{{ site.baseurl }}{% link _gists/name-of-gist.md %}){:title="Click to Visit the {{ gist.title }} page of the Carbon Free Footprint Project at the Concept Library of the MMINAIL"}{:target="_blank"}

{% endfor %}

### Description

{{ site.description }}

{% include raw-code-anchors.md %}

{% include sources-and-uses.md %}

### External Sources

- The [Project Source Links](https://mminail.github.io/CFFP/Source-Carbon-Free-Links.htm){:title="Click to Visit the Source Links page of the Carbon Free Footprint Project at GitHub pages"}{:target="_blank"} page of the Carbon Free Footprint Project. Published by © 2017 - 2018 [Mminail.github.io](https://mminail.github.io/){:title="Click to Visit the Concept Library of the Medical Marijuana Initiative of North America - International Limited, an Arizona Benefit Corporation"}{:target="_blank"}.

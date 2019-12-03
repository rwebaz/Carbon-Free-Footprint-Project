---
title: Northern Lights
layout: default
excerpt: Place the introducing line of text ie.) the 'lead' here ...
hint: Place the intro paragraph ie.) the 'hypothesis' here ...
repo: Carbon-Free-Footprint-Project
ver_date: 11-26-19
navigation_weight: 8
categories: page
---
{% include toc.md %}

## Acquisition

> **Hint**. {{ page.hint }}

The BC Northern Lights Company of British Columbia, Canada was recently merged with Aurora Cannabis, Inc. in a purchase transaction Dtd September #2017 as reported by [Bloomberg](https://www.bloomberg.com/research/stocks/private/snapshot.asp?privcapId=539316036){:title='Click to Visit the Landing page for the BC Northern Lights - Aurora Cannabis merger'}{:target='_blank'}.

## Intellectual Property

{% include venture-cffp.htm %}

## Image Filters

Prepending the `path` and `file name` of an image with simply the `site.baseurl` in liquid can be achieved with the `relative_url` filter.

However, prepending the `path` and `file name` of an image with both the `site.url` and `site.baseurl` in liquid can be achieved only with the `absolute_url` filter.

## BC Northern Lights

An analysis designed to establish a **Carbon Free Footprint** when operating a BC Northern Lights Bloombox 'Full Blast' 24/7.

### Gist Links

The path to this page is ... `{{ page.path }}`

The path to the target page is ...

{% for gist in site.gists %}

- [{{ gist.title }}]({{ site.url }}{{ site.baseurl }}{% link _gists/First-Gist.md %}){:title="Click to Visit the {{ gist.title }} page of the Carbon Free Footprint Project at the Concept Library of the MMINAIL"}{:target="_blank"}

{% endfor %}

## Last Subtitle

More to come ...

***

**Note**. The above synopsis was derived from an article written by Sungevity [[1](#SUNGEVITY){:.red}].

1. {:#SUNGEVITY}[Sungevity](https://www.sungevity.com/get-your-iquote){:title='Click to Visit the Landing page for the Sungevity Solar Powered Promotion'}{:target='_blank'}.

***

{% include patreon-link.md %}

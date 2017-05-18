---
layout: alt-default
title: Markdown Tips | CFFP
---
# GFG

GFM is an acronym for Git Hub Flavor'd Markdown (.md)

- [ ] This is a list item bullet with an open ( space ) check box

## The Command Pallette ( Unordered List )

Note. To access the Command Palette in Visual Studio Code (VSC), press the following three keys simultaneously:

- shift, or '⇧'

- command, or '⌘'

- capital P, or 'P' ; where capital P represents the term "Palette"

**Note**. The trick is to prepend each list item with a `-` hyphen followed by a space before the start of each list item.

## Ordered Lists

To create an ordered list in (.md), begin each list item with the number `1` followed by a single period `.` followed by a space before the text of each list item, as follows:

1. List Item \#1
1. List Item \#2
1. List Item \#3

## Inline Anchor Links

Inline anchor links that point internally to other pages within the repo require a separate bracketed `[page.name]` followed by a relative `/page.url` prepended by the `site.github.url` enveloped in a 'moustache' or liquid variable statement `{\{...}\}`, and enclosed in a single set of parenthesis `(...)`, as follows:

```yaml
[Home Page]({\{ site.github.url }\}/index)
```

**Por ejemplo en vivo**. Just typing along and here comes an inline anchor link! ... Click! ... [Home Page]({{ site.github.url }}/index).

**Note**. To effect an inline anchor link while served relatively at the remote GitHub-Jekyll web server farm, prepend the `/page.url` with the `site.github.url`, as follows:

```yaml
[Solar Electricity]({\{ site.github.url }\}/pages/Solar-Electricity)
```

**Live Example**. Another inline anchor link ... [Solar Electricity]({{ site.github.url }}/pages/Solar-Electricity).

**Note**. The author has placed escape `\` characters where appropriate to neutralize the rendering of the liquid statement in the above illustration.

Please remember to remove the escape `\` characters from the liquid statement when going live.

## Stand Alone External Hyperlinks

Inline hyperlinks with bracketed clickable text `[MMINAIL]` may be followed by the `site.url` simply enclosed in a single set of parenthesis `(...)`, as follows:

```markdown
[MMINAIL](https://mminail.github.io)
```

**Live Example**: A stand alone, clickable text, external hyperlink ... [MMINAIL](https://mminail.github.io).

## Auto External Hyperlinks

Stand alone "auto" URLs that point to external targets may be enclosed in angle brackets `<...>` and optionally prepended by a bracketed `[external.site.name]`, as follows:

```markdown
[MMINAIL] <https://mminail.github.io>
```

**Live Example**: A list item hyperlink

- [MMINAIL] <https://mminail.github.io>

**Note**. All external "auto" URLs must start with `https`.

## Reference Style Hyperlinks

An external `site.url` may also be referenced by an inline bracketed clickable text `[MMINAIL]` followed by a bracketed index number `[1]`, as follows:

**Live Example**. The [MMINAIL][1] link in this paragraph is anchored by a citation in the `nofooter` below.

As now revealed ...

```markdown
The [MMINAIL][1] link in this paragraph ...
```

The citation below is comprised of the aforementioned bracketed index number `[1]` followed by a colon `:` followed by the `site.url` of the targeted destination.

**Note**. The citation actually sits below this fifth paragraph of text, hidden in the `nofooter` of this example.

[1]:https://mminail.github.io

But, can now become manifest, as next illustrated ...

```markdown
[1]:https://mminail.github.io
```

## Anchor Links w Site Base URL Using the Optional liquid link tag

Internal anchor links may be served locally or remotely using the optional liquid link tag.

Here, the bracketed clickable text `[Solar Electricity]` is followed by a single set of parenthesis `(...)`.

Inside the single set of parenthesis `(...)` is a double set of braces ie.) a 'moustache' `{\{...}\}` statement that references a liquid variable, in this case ... the site base URL `site.baseurl` followed by another liquid `{\%...\%}` statement that houses the liquid `link` keyword plus a `space` followed by the relative `page` URL of the targeted page `pages/Solar-Electricity.md`.

Using a Triple-backtick highlighted code block with a language qualifier of yaml to illustrate ... all together now!

```yaml
[Solar Electricity]({\{ site.baseurl }\}{\% link pages/Solar-Electricity.md \%})
```

**Note**. The author has also placed escape `\` characters where appropriate to neutralize the rendering of the liquid variable statements within the illustrated code block above.

Please remember to remove the escape `\` characters from the liquid variable statements when going live, as follows:

[Solar Electricity]({{ site.baseurl }}{% link pages/Solar-Electricity.md %})

## Single Backticks

Rule. Single Back-ticks in GFM will create an inline code block.

The VSC default colors for a code block are ...

- `gold color'd text`

- `dark grey background`

## Triple Backticks

**Rule**. Triple Back-ticks ```.`.`.`.``` in GFM will create an multi-line, or "Fenced" code block.

Always remember to place a language qualifier `html` after the first set of triple backticks when highlighting a multi-line block of code in a `(.md)` page.

Por ejemplo, here is a block of Html that has a set of Triple Back-ticks starting the lines both above and below the code block.

```html
<h1>Title</h2>
<p>Lots of code in here ...</p>
<span>Footer text</span>
```

**Note**. The language qualifier `html` has been appended to the first line of Triple Back-ticks immediately 'above' the code block.

Also, similar to the `(.md)` requirement that a blank line follow a Subtitle, the immediately 'below' set of Triple Back-ticks requires a blank line following, as well.

## Snippet Insertion

Simply select a batch of plain text and open up the Command Palette in VSC ...

Next, type `Insert Snippet`.

## Emoji

Support for emoji in VSC on a (.md) does not exist:

`@rwebaz:+1:`

Go to Git Hub comments to render Emoji

Format ...

:musical_note:

## Italic Text

Text that you wish to be italicized go between ... *single asterisk*

## Bold Text

Text that you wish to look emboldened such as a **Note**. Prefix ... Go between a set of double asterisks `**`...`**`, as follows:

**Double Asterisks**

## Inline Images

Inline images may be displayed using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a relative `URL` enclosed in a single set of parenthesis `(...)`, as follows:

![Logo Badge](/..ico/ms-icon-70x70.png)

## Referenced Images

Referenced images may be displayed using the exclamation point `!` followed by a bracketed `[Alt Text]` followed by a bracketed index number `[2]`, as follows:

![ePub Badge][2]

The bracketed index number represents a citation below embedded in the `nofooter` of this example.

The citation is the bracketed index number `[2]` followed by a colon `:` followed by the raw `URL` followed by the title to the photo.

Note. The title to the photo is enveloped in a set of double `"..."` quotes.

When the mouse is hovered over the photo the title given will appear.

**Warning**. The Reference-style method for serving links and images will not work on duplicate index numbers attempting to render multiple objects on the same page.

Therefore, always use a separate index number for each set of Reference-style links or images.

As above in the *Reference Style Hyperlink* section, the citation actually sits below this paragraph of text, hidden in the `nofooter` of this example.

[2]:
https://mminail.github.io/images/png/dot-epub-button-62-x-20.png
"The Official Logo Badge of ePub"

## Blockquote

A blockquote may be started with a single right angle bracket ( greater than ) symbol:

>This is a blockquote with an Reference-style image below:

![CFFP Logo Banner][3]

As above in the *Reference Style Hyperlink* section, the citation actually sits below this paragraph of text, hidden in the `nofooter` of this example.

[2]:
https://rwebaz.github.io/carbon-free-footprint-project/docs/assets/img/svg/ghp-git-hub-pages-medmjorg-carbon-free-footprint-project-flammarion-got-tree-final-banner-1200-x-230.svg
"The Official CFFP Logo Banner"

## Unstyled Hard Returns

The Unstyled Hard Return counterpart in Html `<hr />` may be reproduced in a `(.md)` page using triple asterisks `***`, as follows:

***

But, not above or below Subtitles.

**Note**. By default, the single hash `#` placed at the beginning of a line in a `(.md)` page yields the traditional Html `<h1>Title</h1>` header tag with an automatically generated unstyled hard return placed below.

## Subtitles

Subtitles without a hard return below may be invoked in a `(.md)` page with a set of double hash `##` placed at the beginning of any line thus yielding the traditional Html `<h2>Title</h2>` header tag.

## Cross Out Text

How do you cross-out text in a `(.md)` page?

Simple ... Prepend ie.) place at the beginning and Append ie.) place at the end, a double set of enveloping tildes `~~...~~~` that surround the targeted text, as follows:

~~Cross Dis Sh't~~ ... out!

## Listing Image Assets

Listing the various image assets of your repo require a liquid tag statement placed within a `(.htm)` page, as follows:

```yaml
{\% assign image_files = site.static_files | where: "image", true \%}
{\% for myimage in image_files \%}
  {\{ myimage.path }\}
{\% endfor \%}
```

**Note**. Remember to place a language qualifier `yaml` after the first set of triple backticks when highlighting a multi-line block of code in a `(.md)` page.

Here, the author has also placed an escape `\` character where appropriate to neutralize the rendering of the liquid statement. Please remember to remove the escape `\` characters from the liquid statement when going live.

## List of Git Hub Users

This little combo snippet will render a list of GitHub users associated with your repo, as follows:


```html
<ul>
{\% for member in site.data.members \%}
  <li>
    <a href="https://github.com/{{ member.github }}">
      {\{ member.name }\}
    </a>
  </li>
{\% endfor \%}
</ul>
```

## More To Come

As more snippets are generated or found, expect this list to grow.
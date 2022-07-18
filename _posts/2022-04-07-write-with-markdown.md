---
layout: singlepost
title: "Write a blog with Markdown and Jekyll"
author: "Eric Yeh"
date: 2022-04-07
tags: 
  - blogging
  - coding
permalink: /blog/:title
excerpt: "Markdown is a language that converts plain text to HTML"
---

* TOC
{:toc}


# Overview

<p>The first paragraph</p>

<p>The second paragraph</p>

# Markdown

## link

The link can be tagged to a phrase by enclosing the pharase with square bracket \[words\] 
This is the link: [My website](https://ericyeh-dr.github.io)

Or the link can be directly shown with \<url\>. Take a look at this link: <http://www.markdownguide.org>

## divider

A divider is 3 \* in a row: \*\*\*

Output:
***

## Unordered list

Add \- in front of each item like:
\- item 1
\- item 2
\- item 3

Output:
- list 1
- list 2
- list 3

## blockquote

(need to add CSS)
> This is the second important quote.

## Table

This is a table
\| Syntax      \| Description \|
\| ----------- \| ----------- \|
\| Header      \| Title       \|
\| Paragraph   \| Text        \|


Output:
| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## inline code

inline codes are written like this `print("Hello world!")`
Highlight importance <mark>very important words</mark>

## code block

{% highlight python %}
def bubble_sort(items):
    """ Implementation of bubble sort """
    for i in range(len(items)):
        for j in range(len(items)-1-i):
            if items[j] > items[j+1]:
                # Swap!
                items[j], items[j+1] = items[j+1], items[j]
{% endhighlight %}

# Latex

## Math equation

{% raw %}
  $$a^2 + b^2 = c^2$$
{% endraw %}

# CSS

## Callout

<div class="callout callout-default">
  This is a default callout.
</div>









  




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

<p>This post is served as a note when I learned Markdown and Jekyll and as a reference for me in case I need to brush up my memories.</p>

# What is Markdown

<p>Markdown is a language that allows you to format a document. 
Markdown is extremely versatile and allows you to do pretty much anything you can think of during your writing process. 
For example, making a big title, inserting an image, highlighting an important sentence. </p>

# What is Jekyll

<p>Jekyll is a tool to build static webpages using templates and markdown languages.
It means that you just have to write the content with markdown and specify which templates your want to apply, Jekyll will build the html file for that page for you.</p>



## link

The link can be tagged to a phrase by enclosing the pharase with square bracket \[words\] <br>
This is an example link: [My website](https://ericyeh-dr.github.io)<br>
<br>
Or the link can be directly shown with \<url\>. Take a look at this link: <http://www.markdownguide.org>

## divider

A divider is 3 \* in a row: \*\*\*

Output:

***

## Unordered list

Add \- in front of each item like:<br>
\- item 1<br>
\- item 2<br>
\- item 3<br>

Output:

- list 1
- list 2
- list 3

## blockquote

(need to add CSS)

> This is the second important quote.

## Table

This is a table<br>
\| Syntax      \| Description \|<br>
\| ----------- \| ----------- \|<br>
\| Header      \| Title       \|<br>
\| Paragraph   \| Text        \|<br>


Output:

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title       |
| Paragraph   | Text        |

## inline code

inline codes are written like this `print("Hello world!")`<br>
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









  




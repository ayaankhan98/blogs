---
title: First Post (Testing My Blogs)
author: ayaankhan98
date: 2020-10-22 15:37:00 +0800
categories: [Blogging, Testing]
tags: [Testing]
math: true
---

This post is just a testing post. i was thinking to setup my blogs since last year but i am really very good at delaying things, i tried to setup it many times but... Finally this time somehow i convinced myself and therefore i am just testing this setup. 


## Testing Markdown Title

Some sample text....

Some sample text....

Some sample text....

Some sample text....

# HTML Testing

<h1>This is an H1 Heading</h1>
<h2>This is an H2 Heading</h2>
<h3>This is an H3 Heading</h3>
<h4>This is an H4 Heading</h4>

## List

### Ordered list

1. first item
2. second item
3. third item

### Unordered list

- item 1
	- sub item 1
	- sub item 2

- item 2

## Block Quote

> This line to shows the Block Quote.

## Tables

| Company                      | contact          | Country |
|:-----------------------------|:-----------------|--------:|
| Alfreds Futterkiste          | Maria Anders     | Germany |
| Island Trading               | Helen Bennett    | UK      |
| Magazzini Alimentari Riuniti | Giovanni Rovelli | Italy   |

## Link

<http://127.0.0.1:4000>


## Footnote

Click the hook will locate the footnote[^footnote].

## Inline code

This is an example of `Inline Code`.

## Mathematics

The mathematics powered by [**MathJax**](https://www.mathjax.org/):

$$ \sum_{n=1}^\infty 1/n^2 = \frac{\pi^2}{6} $$

When \\(a \ne 0\\), there are two solutions to \\(ax^2 + bx + c = 0\\) and they are

$$ x = {-b \pm \sqrt{b^2-4ac} \over 2a} $$

## Code Snippet

### Common

```
This is a common code snippet, without syntax highlight and line number.
```

### Specific Languages

#### Console

```console
$ date
Sun Nov  3 15:11:12 CST 2019
```


#### Terminal

```terminal
$ env |grep SHELL
SHELL=/usr/local/bin/bash
PYENV_SHELL=bash
```

#### Ruby

```ruby
def sum_eq_n?(arr, n)
  return true if arr.empty? && n == 0
  arr.product(arr).reject { |a,b| a == b }.any? { |a,b| a + b == n }
end
```

#### Shell

```shell
if [ $? -ne 0 ]; then
    echo "The command was not successful.";
    #do the needful / exit
fi;
```

#### Liquid

{% raw %}
```liquid
{% if product.title contains 'Pack' %}
  This product's title contains the word Pack.
{% endif %}
```
{% endraw %}

#### HTML

```html
<div class="sidenav">
  <a href="#contact">Contact</a>
  <button class="dropdown-btn">Dropdown
    <i class="fa fa-caret-down"></i>
  </button>
  <div class="dropdown-container">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
  </div>
  <a href="#contact">Search</a>
</div>
```

**Horizontal Scrolling**

```html
<div class="panel-group">
  <div class="panel panel-default">
    <div class="panel-heading" id="{{ category_name }}">
      <i class="far fa-folder"></i>
      <p>This is a very long long long long long long long long long long long long long long long long long long long long long line.</p>
      </a>
    </div>
  </div>
</div>
```


## Reverse Footnote

[^footnote]: The footnote source.
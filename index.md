---
title: CommonMark for Humans
permalink: /
---

<style>
h3:not(:first-of-type) {
    margin-top: 36px;
}
</style>

The [CommonMark](http://spec.commonmark.org/0.28/) is a little complicated to digest, and the often referenced [Github guide](https://guides.github.com/features/mastering-markdown/) (which this page contains parts of) has snippets which only apply to GitHub.  This page is a simple reference guide showing you how to complete the most common tasks.

It's worth remembering that anywhere that allows you to use CommonMark can usually allow you to use basic HTML as well, so you may not need to use this guide!

* Table of Contents
{:toc}

### Headers

You must have a space between the hash and the text for the heading to appear.

```md
# This is a <h1> tag
## This is a <h2> tag
### This is a <h3> tag
#### This is a <h4> tag
##### This is a <h5> tag
###### This is a <h6> tag
```

An alternative method is to put dashes on the following line:

```md
This is a <h1> tag
------------------

This is a <h2> tag
------------------
```


### Text manipulation

```md
*This text will be italic*
_This will also be italic_

**This text will be bold**
__This will also be bold__

_You **can** combine them_
```


### Lists

#### Unordered

```md
* Item 1
* Item 2
  * Item 2a
  * Item 2b
```

#### Ordered

```md
1. Item 1
1. Item 2
1. Item 3
   1. Item 3a
   1. Item 3b
```


### Images

```md
![GitHub Logo](/images/logo.png)
Format: ![Alt Text](url)
```


### Links

```md
http://github.com - automatic!
[GitHub](http://github.com)
```

An alternative option is to use reference links.

```md
The user guide[1] states that you *must* use a password[2].

[1]: /user-guide/
[2]: /user-guide/#passwords-required
```


### Blockquotes

```md
As Kanye West said:

> We're living the future so
> the present is our past.
```


### Horizontal rules

```md
***
---
–––
- - -
```


### Inline code

```md
I think you should use an `<addr>` element here instead.
```


### Code blocks

~~~md
```
<html>
  <head>
    <title>Hello world!</title>
  </head>
</html>
```
~~~

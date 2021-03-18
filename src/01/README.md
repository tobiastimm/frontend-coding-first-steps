# Exercise 01 - Welcome to HTML

👋 Hello!
I'm glad you are here with me, and we can start your incredible journey into the world of coding!

We will kick off the first exercise with HTML!

## Lesson

Facebook, Google, Instagram, Twitter, ... and all the websites you are using on a daily basis are built with three technologies. HTML, CSS and JavaScript.

These three magical technologies complement each other and are a must-have to understand how the modern web is working.

The first of these three is HTML.

HTML (Hypertext Markup Language) is, as the name includes, a markup language. The angle brackets `<body>` is typical for a markup language.

HTML is the browser tool for logically structuring our content.
It is the central part needed to be able to display a website.

A markup language uses tags to describe elements and structures like `<body></body>`.

Therefore each element should have an opening and a closing tag.

You can nest an element within the opening and closing tag of another element; you call that nested element a child.

```html
<body>
  <div></div>
</body>
```

> If your element does not have any children, you can also use a so-called self-closing tag `<div />`.

For configuring a tag, you can define attributes. An attribute always consists of three parts `Name="Value"`. To define such an attribute on a tag, add it before the first closing angle bracket `<body id="test"></body>`.

Every `.html` file starts with a `<!doctype html>`. This signalises the browser that this is a [HTML5](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5) document (Don't worry about what HTML5 or HTML4.1 is yet, the modern browsers are all using HTML5).

An HTML document consists of mainly three parts.

- Header
- Body
- Footer

### Header

First of, the header. It is the first element coming directly after the `<html>` tag.
Within the header `<head></head>`, you include information like the page title, link CSS files for styling, and also include some essential JavaScript files to be executed first.

The browser always interprets HTML files from top to bottom, so the parts linked within the `<head />` should be the most important ones that need to be loaded first!

A typical `<head />` could look like this.

```html
<html>
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Exercise 00 - Welcome</title>
    <link rel="stylesheet" href="../../styles/global.css" />
    <link rel="stylesheet" href="./index.css" />
  </head>
</html>
```

To get a bit more in-depth explanation of these lines.

`<meta charset="UTF-8">` is a meta tag for information like the used [charset](https://www.w3schools.com/html/html_charset.asp)

`<meta name="viewport" content="width=device-width, initial-scale=1.0" />` is also a meta tag, but this one describes how the browser should interpret the viewport (this is important if you want to have a correctly working responsible website).

`<title>` is the tag used for setting a title.

`<link />` tags are used for linking scripts or stylesheets with your HTML document.

## Goals

Create your first `.html` document with the title "My First HTML Site".

## Tips

- To make it easier for you to remember which technologies are responsible for which part, you can remember:
  - HTML for logical structure (What I want to display)
  - CSS to style content (How I wish my content to be displayed)
  - JS for adding dynamic stuff and programming (What should happen if I hover over my content)
- The `<head />` is the first tag directly after the `<html>` tag
- [SELFHTML](https://wiki.selfhtml.org/) (German only)
- [Learn HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML)

## Extra Credit

Display the title of the page within a headline on the `<body />`.

[Prev](../00/README.md) • [Next](../02/README.md)

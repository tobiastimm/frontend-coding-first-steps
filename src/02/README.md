# Exercise 02 - Working on the body

## Lesson

In the last lesson, we have talked about the `<head />` section. Now comes the `<body />`.

You could argue that this is the essential part of an HTML website. All the content of a page belongs within the body (even the footer!).

In the past, developers used the `<body />` mainly to add all the structural and logical elements, and everything else like `<script />` tags (for loading script files) belonged within the `<head />`.

Nowadays this has slightly changed.
Many blank pages caused a rethinking because the page is not fully displayed till the browser appropriately loaded the head. So the modern best practices recommend loading most of the `<script />` files at the bottom of the body and only put essential ones within the `<head />`. These are the `critical files`.

We can start now adding content to our website. The most simple one is adding pure text within the `<body></body>` tag, which is fine.

```html
<body>
  This is my first website
</body>
```

> If you put text between the opening and closing tag, it is called a #text node

If this were everything we can do in HTML, most of our websites would be pretty dull. So let's get into our first structural component, the `<div />`.

Imagine the `<div />` as an all-purpose container. In HTML, you use the div to group, structure, and summarize stuff that belongs together.
You can nest as many `<div></div>` as you want.

To make your elements a bit more expressive, you can add so-called attributes to an element.
With this, we could separate our body into logical divs.

```html
<body>
  <div id="headline">This is my first website!</div>
  <div id="description" />
</body>
```

There are additional elements for structuring texts within HTML.

Different headline tags from level one (largest, most important) to level six: `<h1></h1>`, `<h2></h2>`>, ...

It is possible to display text within paragraphs, called `<p>`-tag and lists, tables, images, etc...

We will talk about them in later sections.

With this information, we can start structuring our content even more.

```html
<body>
  <h1>
    This is my first website!
  </h1>
  <p>
    I'm proud of my first website, and I hope you will like it too.
  </p>
</body>
```

## Goals

Improve your first HTML website with a `<body />` and at least one `<div />` or `<p />` tag.

## Tips

- You can find a list of all HTML elements at [MDN](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

## Extra Credit

Try to structure the website even more with different headlines and paragraphs.

[Prev](../01/README.md) • [Next](../03/README.md)

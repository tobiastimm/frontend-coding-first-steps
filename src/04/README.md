# Exercise 04 - Lists

## Lesson

I want to mention some important facts. I want a numbered tasks list, and I want a to-do list.

For all of these needs, you need lists.

In HTML, we can do two kinds of lists, ordered lists `<ol>` and unordered lists `<ul>`.

The `ol` or `ul` will act as a container/group, and they require `<li>` tags to act as a list element.

```html
<ol>
  <li>Grow a long, majestic beard.</li>
  <li>Wear a tall, pointed hat.</li>
  <li>Have I mentioned the beard?</li>
</ol>
```

To create nested lists, you need to add a list to another list.

```html
<ol>
  <li>Grow a long, majestic beard.</li>
  <li>Wear a tall, pointed hat.</li>
  <li>Have I mentioned the beard?</li>
  <ol>
    <li>I'M nested</li>
  </ol>
</ol>
```

> Don't mind the `article`, `ol`, `li` tag. These are just different tags to structure data.

## Goals

Create an unordered to-do list and a table of contents with `ul` and `ol` tags.

## Tips

- [`ul`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ul)
- [`ol`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/ol)

## Extra Credit

Look at some websites and write down where you think it would be wise to use lists to structure content.

Add the results to the `extra.html`.

[Prev](../03/README.md) • [Next](../05/README.md)

# Exercise 08 - Links

## Lesson

This is our last exercise for today!

We haven't covered links yet. There is a critical concept to walk between different pages and connect to the outer world!

A link or an `anchor` is created in HTML via an `a` tag.
You define the destination within the `href` attribute.

This creates a hyperlink to web pages, files, email addresses, locations on the same page, or anything else a URL can address.

```html
<ul>
  <li><a href="https://example.com">Website</a></li>
  <li><a href="mailto:m.bluth@example.com">Email</a></li>
  <li><a href="tel:+123456789">Phone</a></li>
</ul>
```

> Content within each `<a>` tag should indicate the link's destination

You can also link to _"local"_ pages via a relative path.

_*So why do you need links?*_

You don't want to have one big blown-up HTML file for your whole website.
A website is consisting of a lot of different HTML files, sometimes combined separated.

With local links, you can create navigation on your website to navigate the next or previous page.

```html
<ul>
  <li><a href="/">Home</a></li>
  <li><a href="./about.html">About</a></li>
</ul>
```

The `a` also has some additional attributes for specifying how the user is navigated (f.e. new window/tab, same tab, ...).

## Goals

Create a website with an `index.html`, `about.html`, and `imprint.html` and link these three pages with each other.

## Tips

- [`a`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/a)

## Extra Credit

Answer why I can specify `/` instead of `./index.html` to link to the root/home of a website. Add your answer to the `extra.html`.

[Prev](../07/README.md) • [Next](../09/README.md)

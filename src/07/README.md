# Exercise 07 - Inputs

## Lesson

One crucial element missing in our toolkit are the inputs to enter data.

In HTML, there are different kinds of inputs for telephone-numbers, dates, numerics, text, emails, etc. The browser introduced most of them with HTML5.

You can define an `input` via

```html
<div>
  <label for="name">Name (4 to 8 characters):</label>
  <input
    type="text"
    id="name"
    name="name"
    required
    minlength="4"
    maxlength="8"
  />
</div>
```

> Like the `img` tag, the `input` doesn't need a closing or self-closing tag!

You see a lot of attributes here and two new tags. For a good title/name/hint towards information, the web recommends always adding a `label` for an `input`.

To connect these two elements, you need to specify the given `id` of the `input` within the `for` attribute of the `label`.

Besides that, the `input` specifies some validation stuff, like the `minlength` and `maxlength` of the text, an attribute that the input marks as `required`, the `type` of the input, and some naming.

> The `required` attribute doesn't have a value because it is a boolean attribute. That means the value would be `="true"` or `="false"`. Not specifying the attribute equals a falsy value.

## Goals

Create a sign-up form with different kinds of inputs.
Required information for the sign-up area:

- Username
- Email
- Name
- Date of Birth

## Tips

- [`input`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input)
- There is a special type for passwords!

## Extra Credit

Think about different ways to indicate what your input is for. Take a look at `placeholder`s and find some real-life examples on the web! Document your findings in the `extra.html`.

[Prev](../06/README.md) • [Next](../08/README.md)

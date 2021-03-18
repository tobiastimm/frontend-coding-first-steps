# Exercise 05 - Tables

## Lesson

Who doesn't love spreadsheets? I bet everyone has worked with Google Spreadsheets or Excel.
They are an excellent way to structure content in a logical and easy-to-understand manner.

Of course, it is possible to display stuff like that within HTML. The corresponding tag is called `table`.

A table consists of rows `tr` and cells `td`.

```html
<table>
  <tr>
    <td>The table body</td>
    <td>with two columns</td>
  </tr>
</table>
```

Like a document, you can also separate the table into different parts like `thead`, `tbody`and `tfoot`.
For example, you need that to enhance the looks of the columns.

```html
<table>
  <thead>
    <tr>
      <th colspan="1">Name</th>
      <th colspan="2">Surname</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>1</td>
      <td>Max</td>
      <td>Mustermann</td>
    </tr>
  </tbody>
</table>
```

If you create columns within the `thead` it is recommended to use `th` instead of `td`.

> Via the attribute `colspan`, you can stretch a column over multiple cells

## Goals

Create a sign-up table with the columns

- No.
- Name
- Surname
- Nationality
- Address (should span over 2 columns)

## Tips

- [`table`](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/table)

## Extra Credit

Try to enhance your table with a headline and a `tfoot` and add the results to the `extra.html`.

[Prev](../04/README.md) • [Next](../06/README.md)

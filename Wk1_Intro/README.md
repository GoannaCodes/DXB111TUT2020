# HTML:
-`<h1>, <h2>` identify headings
- `<p> `identifies paragraphs
- `<ul> `are unordered lists (bullets), `<ol> `are ordered lists (numberical)
  - ` <li>` are items in a list
- `<a>` identify links as anchors.
  - anchors have url using href `<a href="https://www.google.com.au">`

# CSS:
- selectors denote the elements that will be styled
- properties of an element can be changed by specifying a value
  - i.e. `h1 { color: red }` changes font color of `<h1>` to red
  - `h1 {...}` is the selector & `color: red` is the property
- IDs uses a hash `#elementID` and can not be reused for other elements. Has higher precedent than classes.
- classes `.elementClass` can be reused for multiple elements if they share the same styling.
  - i.e. font styles for `<h1>` and `<p>` that share the class `.intro`

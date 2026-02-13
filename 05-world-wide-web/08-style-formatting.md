# Style & Formatting

HTML lets you control the appearance of your pages in several ways. One simple method is **inline styling**, which uses the `style` attribute inside HTML tags. 

You have already used structural tags like `<h1>` and `<p>`. By default:
- `<h1>` displays large, bold heading text  
- `<p>` displays standard paragraph text  

But what if you want to change colors, fonts, or alignment? Inline styles allow you to do this.

## Inline Style Syntax

You can add styles directly to an HTML element using the `style` attribute (`style = "property:value;").

- A **property** is what you want to change (e.g., `color`)  
- A **value** is the setting you apply (e.g., `blue`)  
- Each property–value pair ends with a semicolon  

## Example

```html
<body>
  <h1 style="color:blue; text-align:center;">This is a Heading</h1>
  <p style="background-color:powderblue; font-family:courier;">
    This is a paragraph.
  </p>
  <p><a href="page2.html">Link to page 2.</a></p>
</body>
```

**Syntax:** `style="property:value;"`.

- A **property** is what you want to change (e.g., `color`)  
- A **value** is the setting you apply (e.g., `blue`)  
- Each property–value pair ends with a semicolon  

## Example

```html
<body>
  <h1 style="color:blue; text-align:center;">This is a Heading</h1>
  <p style="background-color:powderblue; font-family:courier;">
    This is a paragraph.
  </p>
  <p><a href="page2.html">Link to page 2.</a></p>
</body>
```

## More Examples

```HTML
<! -- blue, centered heading -->
<h1 style="color:blue; text-align:center;">Hello World!</h1>
```

```HTML
<! -- paragraph with background color and font -->
<p style="background-color:powderblue; font-family:courier;">
  This is my first HTML page.
</p>
```

## Putting It All Together

Inline styles are written inside quotation marks and can include multiple property-value pairs.

```HTML
<body>
  <h1 style="color:blue; text-align:center;">Hello World!</h1>
  <p style="background-color:powderblue; font-family:courier;">
    This is my first HTML page.
  </p>
</body>
```
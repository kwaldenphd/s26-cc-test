# Cascading Style Sheets

You can style HTML elements using the `style` attribute, but this becomes repetitive and hard to maintain if you want the same formatting on many elements. For example, styling every `<h1>` or `<p>` individually would require repeating the same code each time.

**Cascading Style Sheets (CSS)** provide a more efficient and consistent way to control the appearance of your website. With CSS, you can define styles once and apply them across multiple pages. If you’ve used website builders like WordPress, Weebly, or Wix, CSS is a key part of how site “themes” control visual design.

- Learn more: https://www.w3schools.com/css/css_intro.asp

## Creating an External CSS File

Let’s create a simple external stylesheet.

1. Create a new file named `style.css` in your project folder.  
2. Add the following CSS rules:

```css
body { 
  background-color: lightblue;
}

h1 {
  color: white;
  text-align: center;
}

p {
  font-family: courier;
  font-size: 20px;
}

# Adding Content

```{image} ../images/ch5/HTML_Page_Structure.png
:alt: HTML Page Structure
:width: 500px
:align: center
````

Now we can start adding content to the page.

Inside the `<head>` tags, you will see a `<title>` tag. The `<head>` section of an HTML document contains metadata, including the page title, which appears in the browser tab.

```html
<head>
  <title>YOUR PAGE TITLE GOES HERE</title>
</head>
```

Replace `YOUR PAGE TITLE GOES HERE` with your desired page title. Then open the file in a web browser to see the updated title in the browser tab.

Next, let’s add content to the `<body>` section. The `<body>` contains the content that will display in the web browser. HTML provides many formatting tags — you can explore them on [W3Schools "HTML Reference"](https://www.w3schools.com/tags/default.asp).

For now, we’ll use `<h1>` for a main heading and `<p>` for a paragraph.

After the opening `<body>` tag, add a `<h1>` tag on a new line:

> *Note: HTML does not require indentation, but properly indenting your code helps keep it organized.*

```html
<body>
  <h1>Hello World!</h1>
</body>
```

Enter your content between the `<h1>` and `</h1>` tags. The `<h1>` tag formats text as a first-level heading.

```{image} ../images/ch5/Image_6.jpg
:alt: Headers
:width: 500px
:align: center
```

Next, add a paragraph using `<p>` tags:

```html
<body>
  <h1>Hello World!</h1>
  <p>This is my first HTML document.</p>
</body>
```

```{warning}
Most desktop text editors do **not** auto-save. Be sure to save your work regularly!
```

```{admonition} Viewing Your Webpage
:class: tip
Save the `.html` file and open it in a web browser to see your updates.
```

<blockquote>
<h1>Why <code>index.html</code>?</h1>
<br>
<code>index.html</code> is the default landing page for websites. Web servers automatically recognize <code>index.html</code> as the home page. Some servers use other variations like <code>home.html</code>, but we will use <code>index.html</code>.
</blockquote>
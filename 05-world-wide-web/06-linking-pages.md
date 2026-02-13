# Linking Pages

Now, let’s add a link to a second page from our `index.html` page.  

We create links using the `<a>` tag and its `href` attribute. The `<a>` tag defines a hyperlink, and the `href` attribute specifies the link’s destination. You can use it to link to another page in your website or to an external website.

The syntax is:

```html
<a href="URL">Text that will appear as the link</a>
```

## Example

On your `index.html` page, below your paragraph, add:

```html
<a href="page2.html">Link to page 2</a>
```

* Learn more about the `<a>` tag on [W3Schools](http://www.w3schools.com/TAGS/att_a_href.asp).

Full example:

```html
<!DOCTYPE html>
<html>
<head>
<title>Page Title</title>
</head>
<body>

<h1>This is a Heading</h1>
<p>This is a paragraph.</p>

<p><a href="page2.html">Link to page 2</a></p>

</body>
</html>
```

Open `index.html` in a web browser to see the link in action.

## Explanation

When you click **“Link to page 2”**, your `page2.html` file should open.

* Since `page2.html` is in the **same folder** as `index.html`, you only need the file name in the `href` attribute. You do **not** need a full URL like `http://www.example.com`.
* **Note:** If your link doesn’t work, try re-typing the quotation marks around the file name. Sometimes copied quotes can be formatted incorrectly.

If `page2.html` were in a different folder, you would need to include the folder path. For example, if it were in a folder called `pages`, the `href` would look like:

```html
<a href="pages/page2.html">Link to page 2</a>
```

## <i class="fa-solid fa-clipboard-question" aria-hidden="true"></i> Application

If you haven’t already, create a second page and link to it from `index.html`.

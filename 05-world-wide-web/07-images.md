# Adding Images

Let’s add an image to your `index.html` page.

First, choose an image you like (from the internet or your personal computer) and save or move it into the **same folder** as your `index.html` file.

The `<img>` tag is similar to the `<a>` tag you used for links. It has two required attributes:

- `src` — the source of the image (file location or URL)  
- `alt` — alternative text that describes the image

The `src` attribute can point to a local file or to an image URL on the web. The `alt` text is used by screen readers and displayed if the image cannot load, so it should briefly describe the image.

## Example

> Learn more about the `img` tag on [W3Schools](http://www.w3schools.com/tags/tag_img.asp).

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

<img src="image.jpg" alt="Description of the image">

</body>
</html>
````

To add your own image, place this line inside the `<body>`:

```html
<img src="imagefilename" alt="Description of image">
```

Replace `imagefilename` with the actual file name of your image. Then open `index.html` in a web browser to check that the image loads correctly.

## Directory Structure

Right now, your project may only have one image. If you start using multiple images, it’s a good idea to organize them in an `images` folder.

1. Create a folder named `images`.
2. Move your image file into that folder.
3. Reload `index.html`.

**What happens?**

To fix any issues, you will need to update the `src` path in your HTML.

**Hint:** Think about the difference between absolute and relative file paths. For example, if your image is in the `images` folder, the tag should look like this:

```html
<img src="images/imagefilename" alt="Description of image">
```

## <i class="fa-solid fa-clipboard-question" aria-hidden="true"></i> Application

If you haven’t already, add an image to your `index.html` page.

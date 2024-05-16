# Writing HTML Boilerplate

![HTML on laptop](https://images.unsplash.com/photo-1583339793403-3d9b001b6008?w=500&auto=format&fit=crop&q=60&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8MTB8fGh0bWx8ZW58MHx8MHx8fDA%3D)

Html boilerplate is the starting point of every website. It defines the basic structure of the web page. Here is a short tutorial on how to write HTML boilerplate.

> Tip: You can generate the entire HTML boilerplate in vscode by typing `!` and then pressing `Tab`.

## 1. Doctype

```html
<!DOCTYPE html>
```

This is the first line of every HTML file. It tells the browser what kind of file it is. Make sure not to forget this part!

## 2. HTML Tag

```html
<html lang="en"></html>
```

This is the main HTML tag. It will wrap around your entire HTML text, and is called the **_root_** element. Make sure to close it at the end of your document!

## 3. The Head Tag

```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Document</title>
</head>
```

This contains some important information about your file.

- **_meta:_** the meta tag gives the browser information about the type of text the page will have, as well as how to display the content appropriately.
- **_title:_** the title tag contains the title of the website, which appears in the tab of the page.

## 4. The Body Tag

```html
<body></body>
```

The body tag is where the rest of your HTML will go. Everything on the document must be nested between the opening and closing body tags.

You can find more information about HTML boilerplate on [MDN](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics)

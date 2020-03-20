---
title: Declaration
layout: page
---

Before you start to create your own HTML files with your desktop editor, we'll show you how to declare and structure the document so that the browser is able to display everything correctly.

HTML documents usually consist of four main parts: The document declaration, the HTML element, the head, and the body.

```html
<!DOCTYPE HTML>
```

The document declaration in the first line of the HTML file declares that the following content of the file is to be interpreted as HTML by the browser.

```html
<html> ... </html>
```

The HTML element encompasses the whole content of the HTML document. All other elements are children of the HTML element. The HTML element contains the `<head></head>` element and the `<body></body>` element as first children.

```html
<head>
<title>Title of the html document</title>
...
</head>
```

The head section contains information about the document (such as title, author and type of characters).

```html
<body>
<h1>This is a heading</h1>
<p>This is a paragraph</p>
...
</body>
```

Whereas the body section contains the visible page content. Together it looks like this:

<iframe src="https://tumwlfe-mooc.srv.mwn.de/api/edx/42" style="width: 100%; height: 400px; border: 1px solid #dedede;" allowfullscreen="true" frameborder="0"></iframe>
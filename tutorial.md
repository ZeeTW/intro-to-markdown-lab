![a picture of a desk](https://images.unsplash.com/photo-1487017159836-4e23ece2e4cf?q=80&w=2071&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

#How to write an HTML Boilerplate

An HTML boilerplate is the basic template needed to set up any HTML document. Here’s a quick guide to writing one:

1. Start with the `<!DOCTYPE html>` Declaration
   This tells the browser that the document is HTML5.

2. Add the Opening and Closing <html> Tags
   `<html lang="en">`

> Here, lang="en" specifies the language as English for accessibility and SEO.

3. Create the <head> Section
   The <head> section includes meta information about the document, like the character set, viewport, and title.

```
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Web Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
```

- `<meta charset="UTF-8">`: Sets the character encoding.
- `<meta name="viewport" content="width=device-width, initial-scale=1.0">`: Ensures the page displays correctly on all devices.
- `<title>My Web Page</title>`: Sets the title displayed in the browser tab.
- `<link rel="stylesheet" href="styles.css">`: Links to an external CSS file for styling.

4. Create the <body> Section
   The <body> tag contains all visible content.

```
<body>
  <h1>Hello, World!</h1>
  <script src="script.js"></script>
</body>
```

- `<h1>Hello, World!</h1>`: Adds a sample heading as a placeholder for content.
- `<script src="script.js"></script>`: Links to an external JavaScript file for functionality.

5. Close the HTML Document
   End the document by closing the <html> tag.

## Complete HTML Boilerplate Example

```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My Web Page</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <h1>Hello, World!</h1>
  <script src="script.js"></script>
</body>
</html>
```

for more [information](https://www.theodinproject.com/lessons/foundations-html-boilerplate).

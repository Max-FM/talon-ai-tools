# Improve Semantics Demo

Open this file in a text editor, highlight the HTML document to be improved, and use the below Talon command to see the improved semantics in action.

## Command to Use

`model improve semantics`

## Description

This command improves the semantics of the provided HTML document, ensuring that the elements used are proper and follow best practices for user accessibility while maintaining the same structure and layout.

## HTML to Improve

```html

<div>
  <h1>Welcome to My Website</h1>
  <div>Click <a href="#">here</a> to learn more.</div>
</div>

```

## Example Output

```html

<html lang="en">
  <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Welcome to My Website</title>
  </head>
  <body>
    <header>
      <h1>Welcome to My Website</h1>
    </header>
    <main>
      <p>Click <a href="#" aria-label="Learn more about my website">here</a> to learn more.</p>
    </main>
  </body>
</html>

```

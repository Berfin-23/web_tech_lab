# Exercise 3

This exercise covers the basics of CSS (Cascading Style Sheets) and how to use them to style HTML documents. Below is an explanation of the various CSS concepts used in this exercise.

## CSS Explained

### What is CSS?
CSS stands for Cascading Style Sheets. It is used to style and layout web pages, including the design, layout, and variations in display for different devices and screen sizes.

### CSS Syntax
CSS is written in a simple syntax that consists of selectors and declarations. A selector points to the HTML element you want to style, and a declaration block contains one or more declarations separated by semicolons.

### Selectors
Selectors are used to select the HTML elements you want to style. Common selectors include element selectors, class selectors, and ID selectors.

### Properties and Values
CSS declarations consist of a property and a value. The property is the style attribute you want to change, and the value is what you want to change it to.

### External CSS
An external CSS file is a separate file containing only CSS. This file can be linked to multiple HTML documents to apply a consistent style across all of them.

## Using the `<link>` Element

To connect an external CSS file to an HTML document, the `<link>` element is used. The `<link>` element is placed inside the `<head>` section of the HTML document.

### Syntax
```html
<link rel="stylesheet" href="style.css">
```
- rel="stylesheet" specifies the relationship between the current document and the linked file.
- href="style.css" specifies the path to the CSS file.

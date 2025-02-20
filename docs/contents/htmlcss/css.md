# CSS Step-by-Step Guide for Beginners  

This guide will help you understand the basics of CSS and how to style a webpage like the Sushi Recipe example.  

---

# **1. What is CSS?**  
CSS (Cascading Style Sheets) is a language used to style HTML elements. It changes how your webpage looks, including colors, fonts, sizes, and layouts.  

A basic CSS file looks like this:  

```css
body {
  background-color: lightblue;
  font-family: Arial, sans-serif;
  color: black;
}
```

---

# **2. How to Link CSS to HTML**  
To apply CSS styles to an HTML page, use the `<link>` tag inside the `<head>` section of your HTML file:  

```html
<link rel="stylesheet" type="text/css" href="css/superstyle.css">
```  

- **rel="stylesheet"**: Indicates the file is a stylesheet.  
- **type="text/css"**: Specifies the file type (CSS).  
- **href**: The path to your CSS file.  

---

# **3. Basic CSS Syntax**  
CSS is written as rules made up of:  

1. **Selector**: The HTML element to style (e.g., `body`, `h1`, or `.class-name`).  
2. **Property**: What you want to style (e.g., `color`, `font-size`).  
3. **Value**: The style setting (e.g., `red`, `16px`).  

```css
selector {
  property: value;
}
```

Example:  

```css
h1 {
  color: blue;
  font-size: 36px;
}
```

---

# **4. Styling the `<body>` Tag**  

The `<body>` tag controls the general style of the webpage. Here's how to add:  

- **Font**: Choose a font family and size.  
- **Margins**: Add space around the content.  
- **Text Alignment**: Align text (left, right, center, justify).  

```css
body {
  font-family: Verdana, Geneva, Tahoma, sans-serif;
  font-size: 16px;
  margin-top: 50px;
  margin-left: 200px;
  margin-right: 200px;
  text-align: justify;
}
```

---

# **5. Styling a `<div>` Element**  

Use a `<div>` with a class (e.g., `class="content"`) to create a styled section. Here's how to:  

- Add a **background color**.  
- Add **padding** (space inside the border).  
- Add a **border**.  

```css
div.content {
  background-color: #FFF5EE;
  padding: 30px;
  border: 2px solid #dcdcdc;
}
```

---

# **6. Styling Headings (`<h1>`, `<h2>`, `<h3>`)**  

Headings often have unique styles for emphasis:  

- **Font Size**: Controls the text size.  
- **Color**: Sets the text color.  
- **Borders**: Adds a line above, below, or beside the heading.  

```css
h1 {
  font-size: 36px;
  color: steelblue;
  border-bottom: 3px solid steelblue;
}

h2 {
  font-size: 28px;
  color: #696969;
  border-left: 7px solid steelblue;
  padding-left: 10px;
}

h3 {
  font-style: italic;
  font-size: 20px;
  color: steelblue;
  font-family: 'Times New Roman', Times, serif;
}
```

---

# **7. Styling Paragraphs (`<p>`)**  

Paragraphs can be styled for readability:  

- **Text Indent**: Adds space at the beginning of the paragraph.  
- **Font Size**: Sets the size of the text.  

```css
p {
  text-indent: 20px;
  font-size: 16px;
}
```

---

# **8. Styling Blockquotes (`<blockquote>`)**  

Blockquotes are styled for emphasis:  

- **Text Alignment**: Centers the text.  
- **Font Style**: Italicizes and bolds the text.  
- **Borders**: Adds dotted lines above and below.  

```css
blockquote {
  text-align: center;
  font-family: 'Times New Roman', Times, serif;
  font-style: italic;
  font-weight: bold;
  font-size: 28px;
  color: steelblue;
  border-top: 5px dotted steelblue;
  padding-top: 5px;
  border-bottom: 5px dotted steelblue;
  padding-bottom: 5px;
}
```

---

# **9. Styling Images (`<img>`)**  

Images can be styled with borders and padding:  

```css
img {
  border: 2px solid steelblue;
  padding: 5px;
}
```

To align images:  

- Use **float** to position them on the left or right.  
- Add **margins** to create space around them.  

```css
img.right-pic {
  float: right;
  margin-left: 10px;
}

img.left-pic {
  float: left;
  margin-right: 10px;
}
```

---

# **10. Organizing Your Styles**  

Place your CSS rules in a `.css` file (e.g., `superstyle.css`) and save it in the `css/` folder of your project.  

---

# **11. How to Test Your CSS**  

1. Write and save your CSS file.  
2. Open the linked HTML file in your browser.  
3. Refresh the page after making changes to see the updated styles.  

---

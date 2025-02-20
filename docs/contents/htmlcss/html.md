# HTML Step-by-Step Guide for Beginners  

This guide will help you understand the basics of HTML to create a simple website like the Sushi Recipe example.  

---

# **1. What is HTML?**  
HTML (HyperText Markup Language) is the language used to structure web pages. It uses "tags" to tell the browser how to display the content.  

A basic HTML document looks like this:  

```html
<!DOCTYPE html>  
<html>  
  <head>  
    <meta charset="UTF-8">  
    <title>My Web Page</title>  
  </head>  
  <body>  
    <h1>Hello, World!</h1>  
    <p>This is my first web page.</p>  
  </body>  
</html>  
```

---

# **2. The Structure of an HTML File**  

Every HTML file has three main parts:  

1. **`<!DOCTYPE html>`**  
   - This tells the browser that you're using HTML5, the latest version of HTML.  

2. **`<html>`**  
   - The root of the HTML document. Everything goes inside this tag.  

3. **`<head>`**  
   - This is where you put information about your web page, like the title and styles.  

4. **`<body>`**  
   - This is where you write the content that will appear on the web page.

---

# **3. Adding a Title**  
The title is what you see on the browser tab. You can set it using the `<title>` tag inside the `<head>` section:  

```html
<title>Sushi Recipe</title>  
```

---

# **4. Adding Text**  
To add text, use the following tags:  

- **Headings**: Use `<h1>` to `<h6>` to create titles and subtitles.  
  ```html
  <h1>Main Title</h1>  
  <h2>Subtitle</h2>  
  <h3>Smaller Subtitle</h3>  
  ```  

- **Paragraphs**: Use `<p>` to create blocks of text.  
  ```html
  <p>This is a paragraph of text.</p>  
  ```  

- **Bold and Italics**: Use `<b>` for bold and `<i>` for italics.  
  ```html
  <p>This is <b>bold</b> text and this is <i>italic</i> text.</p>  
  ```  

---

# **5. Adding Images**  
To display an image, use the `<img>` tag and specify the `src` (source) and `alt` (alternative text) attributes:  

```html
<img src="images/sushi.png" alt="A delicious sushi dish" width="300">  
```  

- **src**: The path to your image file.  
- **alt**: A description of the image (useful for accessibility).  
- **width**: The size of the image.  

---

# **6. Adding Links**  
To link to another page or website, use the `<a>` tag:  

```html
<a href="https://example.com" target="_blank">Visit Example Website</a>  
```  

- **href**: The link to the website or page.  
- **target="_blank"**: Opens the link in a new tab.

---

# **7. Creating Lists**  
HTML supports two types of lists:  

- **Unordered List**: Use `<ul>` and `<li>` for a bulleted list.  
  ```html
  <ul>  
    <li>First Item</li>  
    <li>Second Item</li>  
  </ul>  
  ```  

- **Ordered List**: Use `<ol>` and `<li>` for a numbered list.  
  ```html
  <ol>  
    <li>Step One</li>  
    <li>Step Two</li>  
  </ol>  
  ```  

---

# **8. Adding Videos**  
To include a YouTube video, use the `<iframe>` tag:  

```html
<iframe  
  width="560"  
  height="315"  
  src="https://www.youtube.com/embed/EGeNKGosXA8"  
  title="YouTube video player"  
  frameborder="0"  
  allowfullscreen>  
</iframe>  
```  

---

# **9. Organizing Your Project**  
When creating a website, it's important to organize your files:  

```
webproject/  
   index.html  
   css/  
      superstyle.css  
   images/  
```  

- **index.html**: The main HTML file.  
- **css/**: A folder for your stylesheets.  
- **images/**: A folder for your image files.

---

# **10. How to Save and Open Your Website**  

1. Write your HTML code in a text editor (e.g., Notepad, Visual Studio Code).  
2. Save the file with the extension `.html` (e.g., `index.html`).  
3. Open the file in any web browser to see your website!  

---

# **11. Compressing Your Project**  

When you’re done, compress your project folder into a ZIP file:  

1. Right-click the folder.  
2. Select **"Send to" > "Compressed (zipped) folder"** (Windows) or **"Compress"** (Mac).  
3. Name the file `webproject.zip`.

---

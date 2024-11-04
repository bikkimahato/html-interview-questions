# HTML Interview Questions and Answers
Welcome to the **HTML Interview Questions and Answers**! This repository is a collection of HTML questions categorized by difficulty level: Easy, Medium, and Hard. Whether you're a beginner looking to understand the basics or an expert aiming to polish your skills, this repository has something for everyone.

## Introduction

HTML (HyperText Markup Language) is the standard markup language for creating web pages and web applications. It is essential for anyone who wants to delve into web development. This repository is designed to help you practice and master HTML by solving a variety of questions ranging from easy to hard.

## Why HTML?

- **Foundation of Web Development**: Understanding HTML is crucial for building web pages and web applications.
- **Easy to Learn**: HTML has a simple syntax that is easy to understand and use.
- **Widely Used**: HTML is the backbone of the web, and mastering it opens doors to learning other web technologies.

## Question Categories

### Easy

These questions are designed for beginners. They cover basic HTML tags, attributes, and simple page structure.

### Medium

These questions are for those who have a basic understanding of HTML and want to delve deeper. They cover forms, tables, and more complex page layouts.

### Hard

These questions are for advanced users who want to test their knowledge and tackle challenging scenarios. They include advanced HTML5 features, multimedia, and semantic elements.

## Contributing

We welcome contributions from the community! If you have a question that you think should be included, please follow these steps:

1. Fork the repository.
2. Create a new branch for your question.
3. Add your question in the appropriate category folder (`easy`, `medium`, `hard`).
4. Submit a pull request with a detailed description of your changes.

---

Happy coding! If you find this repository helpful, please give it a star ⭐ and share it with others.

---

### Table of Contents
### Level : Easy
| No. | Questions |
| --- | --------- |
| 1   | [What does HTML stand for?](#1-what-does-html-stand-for) |
| 2   | [What is the purpose of the `<head>` tag in HTML?](#2-what-is-the-purpose-of-the-head-tag-in-html) |
| 3   | [How do you create a hyperlink in HTML?](#3-how-do-you-create-a-hyperlink-in-html) |
| 4   | [What is the difference between the `<strong>` and `<b>` tags?](#4-what-is-the-difference-between-the-strong-and-b-tags) |
| 5   | [How do you add an image to a webpage?](#5-how-do-you-add-an-image-to-a-webpage) |
| 6   | [What are HTML attributes?](#6-what-are-html-attributes) |
| 7   | [How do you create a list in HTML?](#7-how-do-you-create-a-list-in-html) |
| 8   | [Explain the difference between an ordered list and an unordered list.](#8-explain-the-difference-between-an-ordered-list-and-an-unordered-list) |
| 9   | [How do you create a table in HTML?](#9-how-do-you-create-a-table-in-html) |
| 10  | [What is the `<a>` tag used for?](#10-what-is-the-a-tag-used-for) |
| 11  | [How do you add comments in HTML?](#11-how-do-you-add-comments-in-html) |
| 12  | [What is the purpose of the `<title>` tag?](#12-what-is-the-purpose-of-the-title-tag) |
| 13  | [What is the difference between the `<div>` and `<span>` tags?](#13-what-is-the-difference-between-the-div-and-span-tags) |
| 14  | [How do you create a form in HTML?](#14-how-do-you-create-a-form-in-html) |
| 15  | [What is the purpose of the `<br>` tag?](#15-what-is-the-purpose-of-the-br-tag) |
| 16  | [How do you define a paragraph in HTML?](#16-how-do-you-define-a-paragraph-in-html) |
| 17  | [What is the difference between HTML elements and tags?](#17-what-is-the-difference-between-html-elements-and-tags) |
| 18  | [What is the purpose of the `alt` attribute in the `<img>` tag?](#18-what-is-the-purpose-of-the-alt-attribute-in-the-img-tag) |
| 19  | [How do you specify the language of an HTML document?](#19-how-do-you-specify-the-language-of-an-html-document) |
| 20  | [What is the difference between block-level and inline elements?](#20-what-is-the-difference-between-block-level-and-inline-elements) |
| 21  | [How do you create a checkbox in HTML?](#21-how-do-you-create-a-checkbox-in-html) |
| 22  | [How do you add a video to a webpage?](#22-how-do-you-add-a-video-to-a-webpage) |
| 23  | [What are semantic HTML elements?](#23-what-are-semantic-html-elements) |
| 24  | [How do you create a drop-down list in HTML?](#24-how-do-you-create-a-drop-down-list-in-html) |
| 25  | [What is the purpose of the `charset` attribute in the `<meta>` tag?](#25-what-is-the-purpose-of-the-charset-attribute-in-the-meta-tag) |

### Easy HTML Interview Questions

#### 1. What does HTML stand for?
HTML stands for HyperText Markup Language. It's a standard language used for creating webpages and web applications.

#### 2. What is the purpose of the `<head>` tag in HTML?
The `<head>` tag contains meta-information about the HTML document, such as its title, character set, styles, and scripts. This information is not displayed on the webpage but is essential for proper functioning.

#### 3. How do you create a hyperlink in HTML?
You create a hyperlink using the `<a>` tag with the `href` attribute specifying the URL of the link destination.
```html
<a href="https://www.example.com">Visit Example</a>
```
 **[⬆ Back to Top](#level--easy)**

#### 4. What is the difference between the `<strong>` and `<b>` tags?
The `<strong>` tag indicates strong importance and also conveys semantic meaning, whereas the `<b>` tag simply applies bold styling.
```html
<strong>This is important text.</strong>
<b>This is bold text.</b>
```
 **[⬆ Back to Top](#level--easy)**

#### 5. How do you add an image to a webpage?
Use the `<img>` tag with the `src` attribute for the image path and the `alt` attribute for alternative text.
```html
<img src="image.jpg" alt="Description of the image">
```
 **[⬆ Back to Top](#level--easy)**

#### 6. What are HTML attributes?
HTML attributes provide additional information about HTML elements. They are always included in the opening tag and usually come in name/value pairs like `name="value"`.
```html
<a href="https://www.example.com" target="_blank" title="Example site">Visit Example</a>
```
 **[⬆ Back to Top](#level--easy)**

#### 7. How do you create a list in HTML?
You create lists using the `<ul>` (unordered list) or `<ol>` (ordered list) tags, with each list item enclosed in `<li>` tags.
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```
 **[⬆ Back to Top](#level--easy)**

#### 8. Explain the difference between an ordered list and an unordered list.
An ordered list (`<ol>`) numbers each list item, while an unordered list (`<ul>`) uses bullet points.
```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>

<ul>
  <li>First item</li>
  <li>Second item</li>
</ul>
```
 **[⬆ Back to Top](#level--easy)**

#### 9. How do you create a table in HTML?
Use the `<table>` tag along with `<tr>` (table row), `<th>` (table header), and `<td>` (table data) tags.
```html
<table>
  <tr>
    <th>Header 1</th>
    <th>Header 2</th>
  </tr>
  <tr>
    <td>Data 1</td>
    <td>Data 2</td>
  </tr>
</table>
```
 **[⬆ Back to Top](#level--easy)**

#### 10. What is the `<a>` tag used for?
The `<a>` tag creates hyperlinks, with the `href` attribute specifying the URL of the link destination.
```html
<a href="https://www.example.com">Click here</a>
```
 **[⬆ Back to Top](#level--easy)**

#### 11. How do you add comments in HTML?
Use the `<!-- -->` syntax for comments, which are not displayed by the browser.
```html
<!-- This is a comment -->
<p>This is a paragraph.</p>
```
 **[⬆ Back to Top](#level--easy)**

#### 12. What is the purpose of the `<title>` tag?
The `<title>` tag defines the title of the HTML document, displayed in the browser's title bar or tab. It is placed within the `<head>` tag.
```html
<head>
  <title>My Webpage</title>
</head>
```
 **[⬆ Back to Top](#level--easy)**

#### 13. What is the difference between the `<div>` and `<span>` tags?
The `<div>` tag is a block-level element used to group larger sections of content, while the `<span>` tag is an inline element used to group smaller pieces of content within a block.
```html
<div>This is a block-level element.</div>
<span>This is an inline element.</span>
```
 **[⬆ Back to Top](#level--easy)**

#### 14. How do you create a form in HTML?
Use the `<form>` tag along with form elements like `<input>`, `<textarea>`, `<select>`, and `<button>`.
```html
<form action="/submit" method="post">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <button type="submit">Submit</button>
</form>
```
 **[⬆ Back to Top](#level--easy)**

#### 15. What is the purpose of the `<br>` tag?
The `<br>` tag inserts a line break, forcing the text to move to the next line. It is an empty tag, meaning it has no closing tag.
```html
<p>This is the first line.<br>This is the second line.</p>
```
 **[⬆ Back to Top](#level--easy)**

#### 16. How do you define a paragraph in HTML?
A paragraph is defined using the `<p>` tag. It creates a block of text separated by a margin from adjacent content.
```html
<p>This is a paragraph.</p>
```
 **[⬆ Back to Top](#level--easy)**

#### 17. What is the difference between HTML elements and tags?
HTML tags are the syntax used to define elements, while HTML elements are the building blocks of HTML documents. Tags are written using angle brackets, whereas elements include the tags and the content within them.
```html
<!-- Tag: <p> -->
<!-- Element: <p>This is a paragraph.</p> -->
<p>This is a paragraph.</p>
```
 **[⬆ Back to Top](#level--easy)**

#### 18. What is the purpose of the `alt` attribute in the `<img>` tag?
The `alt` attribute provides alternative text for an image if it cannot be displayed. It also aids accessibility by describing the image to screen readers.
```html
<img src="image.jpg" alt="Description of the image">
```
 **[⬆ Back to Top](#level--easy)**

#### 19. How do you specify the language of an HTML document?
Use the `lang` attribute in the `<html>` tag.
```html
<html lang="en">
  <head>
    <title>My Webpage</title>
  </head>
  <body>
    <p>Hello, world!</p>
  </body>
</html>
```
 **[⬆ Back to Top](#level--easy)**

#### 20. What is the difference between block-level and inline elements?
Block-level elements start on a new line and take up the full width available, while inline elements do not start on a new line and only take up as much width as necessary.
```html
<div>This is a block-level element.</div>
<span>This is an inline element.</span>
```
 **[⬆ Back to Top](#level--easy)**

#### 21. How do you create a checkbox in HTML?
Use the `<input>` tag with the `type` attribute set to "checkbox".
```html
<input type="checkbox" id="subscribe" name="subscribe">
<label for="subscribe">Subscribe to newsletter</label>
```
 **[⬆ Back to Top](#level--easy)**

#### 22. How do you add a video to a webpage?
Use the `<video>` tag with the `src` attribute specifying the video file's path, and optionally include the `controls` attribute to provide playback controls.
```html
<video src="video.mp4" controls>
  Your browser does not support the video tag.
</video>
```
 **[⬆ Back to Top](#level--easy)**

#### 23. What are semantic HTML elements?
Semantic HTML elements clearly describe their meaning and content, improving accessibility and SEO by providing meaningful context to browsers and assistive technologies.
```html
<header>Header content</header>
<nav>Navigation links</nav>
<main>Main content</main>
<article>Article content</article>
<aside>Aside content</aside>
<footer>Footer content</footer>
```
 **[⬆ Back to Top](#level--easy)**

#### 24. How do you create a drop-down list in HTML?
Use the `<select>` tag with nested `<option>` tags for each option.
```html
<label for="fruits">Choose a fruit:</label>
<select id="fruits" name="fruits">
  <option value="apple">Apple</option>
  <option value="banana">Banana</option>
  <option value="cherry">Cherry</option>
</select>
```
 **[⬆ Back to Top](#level--easy)**

#### 25. What is the purpose of the `charset` attribute in the `<meta>` tag?
The `charset` attribute specifies the character encoding for the HTML document, ensuring that it is displayed correctly, especially for special characters and symbols.
```html
<meta charset="UTF-8">
```
 **[⬆ Back to Top](#level--easy)**
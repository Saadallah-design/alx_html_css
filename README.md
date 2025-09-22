# Project: CSS Basic

This project focuses on the fundamentals of CSS, including selectors, properties, and layout techniques. The main goal is to transform a basic HTML structure into a well-styled and responsive webpage using only CSS and HTML.

-----

## Learning Objectives

By the end of this project, you should be able to explain the following concepts without external help:

  * **What is CSS?**: Understand what CSS stands for and its purpose in web development.
  * **How to add style to an element**: Learn the different methods for applying styles to HTML elements, such as inline styles, internal stylesheets, and external stylesheets.
  * **What is a class?**: Define a CSS class and explain its role in applying styles to multiple elements.
  * **What is a selector?**: Understand the function of CSS selectors in targeting specific HTML elements to apply styles.
  * **How to compute CSS Specificity Value**: Grasp the concept of CSS specificity and how the browser determines which styles to apply when there are conflicting rules.
  * **What are Box properties in CSS?**: Explain the CSS Box Model, including properties like `margin`, `border`, `padding`, and `content`.
  * **How does the browser load a webpage?**: Describe the high-level process a web browser follows to render an HTML page with its associated CSS and JavaScript.

-----

## Project Tasks

### 0\. Getting Started

This task involves setting up the project structure. You'll copy existing HTML files (`index.html`, `tweets.html`) from a previous project into a new `css_basic` directory. You will then create two empty CSS files, `base.css` and `styles.css`, and link them to your HTML files.

  * **File Setup**: Create `css_basic` directory and copy the specified HTML files.
  * **Linking Styles**: Add `<link>` tags within the `<head>` of your HTML files to connect them to `base.css` and `styles.css`.

### 1\. Positioning with Flexbox

This section focuses on using **CSS Flexbox** to create a modern and flexible page layout. You will apply `display: flex` and `flex-direction` properties to the `<body>` and `<main>` containers to arrange elements horizontally and vertically. You'll also use the `flex` property to control the size of the `<article>` and `<aside>` elements, giving them a 2:1 width ratio.

  * **Container Styling**: Apply `display: flex` and `flex-direction` to the `<body>` and `<main>` tags to define a flexible layout.
  * **Content Sizing**: Use `flex: 2` on `<article>` and `flex: 1` on `<aside>` to manage their relative widths.
  * **Scrolling**: Add `overflow-y: auto` to `<article>` and `<aside>` to enable vertical scrolling for their content.

### 2\. Responsive Web Design

This task introduces the concept of making your website **responsive**. You'll use a pre-defined CSS class (`works_on_smartphone`) and a **meta viewport tag** to ensure the website's layout adjusts gracefully on different screen sizes, particularly on mobile devices.

  * **Responsive Class**: Add `class="works_on_smartphone"` to the `<body>` tag in `index.html`.
  * **Viewport Tag**: Learn and implement the `meta` tag to control the viewport and scaling on mobile devices.

### 3\. Additional Styling

In this final task, you'll add your own creative flair to the website. You can apply various non-positioning-related CSS rules to `styles.css` to enhance the visual design. This includes changing colors, backgrounds, borders, and more. You're also allowed to add a logo using a Unicode character.

  * **Custom Styling**: Add any desired CSS properties to `styles.css` to change the appearance of elements.
  * **Unicode Logo**: Implement a Unicode character as a logo within the `<header>` element and style it using the `class="logo"` attribute.

-----

### Project Structure

```
alx_html_css/
├── css_basic/
│   ├── index.html
│   ├── tweets.html
│   ├── base.css
│   └── styles.css
├── README.md
```
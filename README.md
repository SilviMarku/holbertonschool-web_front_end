# HTML (HyperText Markup Language) README

HTML is the fundamental language used to structure and create web pages. This README provides guidelines and best practices for creating well-structured and accessible HTML documents.

## Table of Contents
1. [Guidelines for HTML](#1-guidelines-for-html)
2. [Creating the Skeleton of an HTML5 Page](#2-creating-the-skeleton-of-an-html5-page)
3. [Using Semantic HTML Tags](#3-using-semantic-html-tags)
4. [When to Use `<div>` vs. `<span>`](#4-when-to-use-div-vs-span)
5. [Semantic Value of HTML5 Tags](#5-semantic-value-of-html5-tags)
6. [Using Headings](#6-using-headings)
7. [Making Lists in HTML](#7-making-lists-in-html)
8. [Differences Between Media Types](#8-differences-between-media-types)
9. [Structuring Data in a Table](#9-structuring-data-in-a-table)
10. [Integrating Video and Audio](#10-integrating-video-and-audio)
11. [Embedding External Content](#11-embedding-external-content)
12. [Correctly Structuring an HTML Page](#12-correctly-structuring-an-html-page)

---

### 1. Guidelines for HTML
- Follow the latest HTML specifications.
- Use lowercase for HTML tags and attributes.
- Indent and format your code for readability.
- Use comments for documentation.
- Validate your HTML code.

### 2. Creating the Skeleton of an HTML5 Page
- Start with the `<!DOCTYPE html>` declaration.
- Create the `<html>` element.
- Inside `<html>`, include `<head>` and `<body>` elements.
- In the `<head>`, set the document's metadata (e.g., title, character set).
- In the `<body>`, build the content of your web page.

### 3. Using Semantic HTML Tags
- Semantic tags provide meaning and structure to content, aiding accessibility and SEO.
- Examples include `<header>`, `<main>`, `<footer>`, `<article>`, `<nav>`, `<section`, and `<aside>`.
- Instead of using generic `<div>` elements, use semantic tags to better describe the content's purpose.

### 4. When to Use `<div>` vs. `<span>`
- Use `<div>` for block-level containers and grouping.
- Use `<span>` for inline, text-level grouping.
- `<div>` typically contains block-level elements, while `<span>` is for inline elements.

### 5. Semantic Value of HTML5 Tags
- `<header>`: Represents the introductory content of a section or a page.
- `<main>`: Denotes the main content area of a page.
- `<footer>`: Represents the footer of a section or a page.
- `<article>`: Represents a self-contained composition.
- `<nav>`: Represents a section with navigation links.
- `<section>`: Defines a thematic grouping within a document.
- `<aside>`: Represents content tangentially related to the content around it.

### 6. Using Headings
- Use heading tags (`<h1>` to `<h6>`) to create a hierarchical structure.
- Follow the hierarchical order to maintain a clear document structure.
- Headings are crucial for accessibility and SEO.

### 7. Making Lists in HTML
- Use `<ul>` for unordered lists (bulleted).
- Use `<ol>` for ordered lists (numbered).
- Use `<li>` to define list items within `<ul>` or `<ol>`.
- Nest lists for sub-lists.

### 8. Differences Between Media Types
- SVG: Scalable Vector Graphics, ideal for graphics and logos.
- GIF: Graphics Interchange Format, suitable for simple animations.
- PNG: Portable Network Graphics, good for images with transparency.
- JPG: Joint Photographic Experts Group, best for photos with gradients.

### 9. Structuring Data in a Table
- Use the `<table>` element to create a table.
- Use `<tr>` for table rows, `<th>` for table headers, and `<td>` for table data cells.
- Employ `<caption>` to add a table caption.
- Utilize `<thead>`, `<tbody>`, and `<tfoot>`, for table sections.

### 10. Integrating Video and Audio
- Use the `<video>` element to embed videos.
- Use the `<audio>` element to embed audio files.
- Include source files within these elements for cross-browser compatibility.

### 11. Embedding External Content
- Use `<iframe>` to embed external content like maps or external websites.
- Specify the source URL in the `src` attribute.
- Ensure the content you embed is responsive and doesn't break the layout.

### 12. Correctly Structuring an HTML Page
- Follow a well-organized structure, starting with the `<!DOCTYPE>` declaration.
- Use semantic elements for content structure.
- Validate your HTML code using tools like the W3C Markup Validation Service.

---

These guidelines provide a foundation for creating structured, accessible, and well-formatted HTML documents. Incorporating these best practices will help us build effective and visually pleasing web pages.
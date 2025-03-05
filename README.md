**Basic Structure of an HTML Page**
<!DOCTYPE html> <!-- Declares the document type as HTML5 -->
<html> <!-- Root element of the page -->
<head> <!-- Contains metadata and links to styles/scripts -->
    <title>My Page Title</title> <!-- Displays in the browser tab -->
    <meta charset="UTF-8"> <!-- Defines character encoding -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0"> <!-- Makes page responsive -->
</head>
<body> <!-- Contains all visible content -->
</body>
</html>

**Headings & Paragraphs**
<h1> to <h6> <!-- Headings (h1 is the largest, h6 is the smallest) -->
<p> <!-- Paragraph -->
<br> <!-- Line break -->
<hr> <!-- Horizontal rule (divider) -->
<pre> <!-- Preformatted text (preserves spaces & line breaks) -->

**Text Formatting**
<strong> <!-- Important (bold) text -->
<em> <!-- Emphasized (italic) text -->
<b> <!-- Bold text (without emphasis) -->
<i> <!-- Italic text (without emphasis) -->
<u> <!-- Underlined text -->
<mark> <!-- Highlighted text -->
<small> <!-- Smaller text -->
<del> <!-- Deleted text (strikethrough) -->
<ins> <!-- Inserted (underlined) text -->
<sub> <!-- Subscript text (e.g., H₂O) -->
<sup> <!-- Superscript text (e.g., x²) -->
<span> <!-- Inline container (for styling) -->

**Lists**
<ul> <!-- Unordered list -->
<ol> <!-- Ordered list -->
<li> <!-- List item -->
<dl> <!-- Description list -->
<dt> <!-- Term name -->
<dd> <!-- Term description -->

**Links & Images**
<a href="https://example.com" target="_blank">Link</a> <!-- Hyperlink -->
<img src="image.jpg" alt="Description" width="100" height="100"> <!-- Image -->

**Tables**
<table>
    <caption>Table Title</caption>
    <tr>
        <th>Header 1</th>
        <th>Header 2</th>
    </tr>
    <tr>
        <td>Data 1</td>
        <td>Data 2</td>
    </tr>
</table>

**Forms & Inputs**
<form action="submit.php" method="post"> <!-- Form -->
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" placeholder="Enter your name">
    <input type="submit" value="Submit">
</form>

**Semantic HTML (Improves Accessibility & SEO)**
<header> <!-- Page or section header -->
<nav> <!-- Navigation links -->
<article> <!-- Standalone content -->
<section> <!-- Logical sectioning of content -->
<aside> <!-- Sidebar or additional info -->
<footer> <!-- Footer section -->

**Embedded Content**
<video src="video.mp4" controls></video> <!-- Video -->
<audio src="audio.mp3" controls></audio> <!-- Audio -->
<iframe src="https://example.com" width="600" height="400"></iframe> <!-- Embedded page -->
**
Important Attributes**
class="classname" <!-- Groups elements for styling -->
id="uniqueID" <!-- Unique identifier for an element -->
style="color: red;" <!-- Inline CSS styling -->
title="Tooltip text" <!-- Extra info on hover -->

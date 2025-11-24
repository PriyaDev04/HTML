# HTML

1. What are HTML Headings?

HTML headings are defined with the <h1> to <h6> tags.
<h1> is the largest and most important, while <h6> is the smallest.
They help structure content hierarchically and are important for SEO.
CODE 
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
------------------------------------------------------------------------------------------------------

2. What is a Paragraph Tag?

The <p> tag defines a paragraph of text. It automatically adds some space before and after.
CODE 
<p>This is a paragraph of text.</p>
------------------------------------------------------------------------------------------------------

3. What are Formatting Tags in HTML?


Formatting tags style text directly:

<b> / <strong> → bold text / important text

<i> / <em> → italic text / emphasized text

<u> → underline

<mark> → highlight

<sup> / <sub> → superscript/subscript

<small> / <del> / <ins> → small, deleted, inserted text

CODE 
<p>This is <strong>important</strong> and <em>emphasized</em> text.</p>
------------------------------------------------------------------------------------------------------

4. How to Display an Image in HTML?

Use the <img> tag with src and alt attributes.
CODE
<img src="image.jpg" alt="Description of image" width="300">

------------------------------------------------------------------------------------------------------

5. What is an Anchor Tag?


Used to create hyperlinks.
CODE
<a href="https://example.com" target="_blank">Visit Example</a>
-----------------------------------------------------------------------------------------------------

6. What are Lists in HTML?


Ordered list (<ol>) – numbered

Unordered list (<ul>) – bullets

Description list (<dl>) – term and description

CODE
<ul><li>HTML</li><li>CSS</li></ul>

-----------------------------------------------------------------------------------------------------

7. What is a Table in HTML?

Tables organize data in rows and columns.
CODE
<table border="1">
  <tr><th>Name</th><th>Age</th></tr>
  <tr><td>John</td><td>25</td></tr>
</table>
------------------------------------------------------------------------------------------------------
8. What is the id Attribute?


Uniquely identifies an element.

Used for JavaScript or CSS targeting.
CODE
<p id="intro">Welcome!</p>
---------------------------------------------------------------------------------------------------

9. What is the class Attribute?

Groups multiple elements for styling or JS logic.
CODE
<p class="highlight">This is highlighted.</p>
---------------------------------------------------------------------------------------------------

10. What is an Iframe?

Embeds another webpage or media inside a page.
CODE
<iframe src="https://example.com" width="400" height="300"></iframe>
----------------------------------------------------------------------------------------------------

11. What is a <div> Tag?

Defines a block-level container used for layout.
CODE
<div class="container">Content here</div>
---------------------------------------------------------------------------------------------------

12. What is a <span> Tag?

Inline container for styling part of text.
CODE
<p>This is <span style="color:red">important</span>.</p>
-------------------------------------------------------------------------------------------------

13. What is an HTML Form?

Collects user input.
CODE 
<form action="/submit" method="post">
  <label>Name:</label>
  <input type="text" name="name">
  <input type="submit">
</form>
---------------------------------------------------------------------------------------------------

14. What is the <audio> Tag?
Embeds sound content.
CODE
<audio controls>
  <source src="sound.mp3" type="audio/mpeg">
</audio>
---------------------------------------------------------------------------------------------------
15. What is the <video> Tag?

Embeds video content.
<video controls width="400">
  <source src="movie.mp4" type="video/mp4">
</video>
----------------------------------------------------------------------------------------------------

16. Difference Between HTML and HTML5

| Feature       | HTML                | HTML5                                     |
| ------------- | ------------------- | ----------------------------------------- |
| Doctype       | Long & complex      | `<!DOCTYPE html>`                         |
| Audio/Video   | Requires plugins    | `<audio>` & `<video>` supported           |
| Storage       | Cookies only        | LocalStorage & SessionStorage             |
| Graphics      | No built-in support | `<canvas>` & `<svg>`                      |
| Semantic tags | Limited             | `<header>`, `<footer>`, `<section>`, etc. |


--------------------------------------------------------------------------------------------------

17. What is Semantic HTML?

Uses meaningful tags to describe content structure, improving SEO and accessibility.
CODE
<header></header>
<nav></nav>
<main></main>
<section></section>
<footer></footer>
------------------------------------------------------------------------------------------------------
18. What are Global Attributes?

Can be used on any HTML element:
id, class, style, title, hidden, data-*, etc.
------------------------------------------------------------------------------------------------------

19. What are Meta Tags?

Provide metadata about the webpage.
CODE
<meta charset="UTF-8">
<meta name="description" content="HTML interview questions">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
--------------------------------------------------------------------------------------------------

20. What is <!DOCTYPE html>?

Tells the browser which version of HTML to use.
HTML5 uses a simple declaration:
CODE
<!DOCTYPE html>
------------------------------------------------------------------------------------------------------

21.  Advanced Form Elements
HTML5 introduced new input types and elements:
CODE
<input type="email" required>
<input type="date">
<input type="range" min="0" max="100">
<datalist>
  <option value="HTML"><option value="CSS">
</datalist>
------------------------------------------------------------------------------------------------------

22. Difference Between Block and Inline Elements
Block	                                     Inline
Starts on a new line	               Doesn’t start a new line
Takes full width	                    Takes only needed width
Example: <div>, <p>	                    Example: <span>, <a>

------------------------------------------------------------------------------------------------------

23. What are Data Attributes (data-*)?

Used to store custom data for JavaScript.
CODE
<button data-user="pree">Click</button>
---------------------------------------------------------------------------------------------------
24. What are Void Elements?

Elements that do not have closing tags.
CODE
<br>, <img>, <hr>, <input>, <meta>, <link>.
------------------------------------------------------------------------------------------------------

25. What are ARIA and Accessibility Features?

ARIA (Accessible Rich Internet Applications) improves accessibility for users with disabilities.
CODE
<button aria-label="Close Menu">X</button>
-----------------------------------------------------------------------------------------------------

26. What is Local Storage and Session Storage?

Local Storage: Stores data with no expiry.

Session Storage: Stores data for one session (tab).
(Handled via JS, but part of HTML5 APIs.)
------------------------------------------------------------------------------------------------------
27. What is the <canvas> Element?

Used for drawing graphics using JavaScript.
CODE
<canvas id="draw" width="200" height="100"></canvas>
-----------------------------------------------------------------------------------------------------
28. What is the <svg> Tag?

Used for vector-based graphics.
CODE
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" fill="blue" />
</svg>
------------------------------------------------------------------------------------------------------
29. What are async and defer in <script>?

Attribute	          Behavior
async	            Loads and executes script as soon as it’s downloaded.
defer	            Executes after HTML parsing is done.

CODE
<script src="app.js" defer></script>
------------------------------------------------------------------------------------------------------
30. What is a Favicon?

Small icon shown in the browser tab.
CODE
<link rel="icon" href="favicon.ico">
------------------------------------------------------------------------------------------------------
31. What is Responsive Design in HTML?

HTML supports responsive layouts with
CODE
<meta name="viewport" content="width=device-width, initial-scale=1.0">
This ensures the webpage scales correctly on all devices.
-----------------------------------------------------------------------------------------------------

32. What is the DOM in HTML?

The Document Object Model is a tree structure representation of HTML elements that JavaScript can access and modify dynamically.
-----------------------------------------------------------------------------------------------------

33. What are Deprecated Tags in HTML5?

Tags no longer recommended: <center>, <font>, <big>, <u>, <marquee>, <frameset>.
------------------------------------------------------------------------------------------------------
34. Difference Between HTML, XHTML, and XML
| Feature        | HTML     | XHTML    | XML         |
| -------------- | -------- | -------- | ----------- |
| Case-sensitive | No       | Yes      | Yes         |
| Closing tags   | Optional | Required | Required    |
| Syntax         | Flexible | Strict   | Very strict |

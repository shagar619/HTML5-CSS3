<!-- markdownlint-disable MD012 MD026 MD001 MD022 MD032 MD029 MD019 MD034 MD031 MD047 MD040 MD009 MD058 MD024 MD033 MD041 MD045 MD007 MD036 MD028  -->

<div>

 <img src="https://i.ibb.co.com/4wYVbmMC/985-9857805-html5-css3-logo-png-html-and-css-logo.jpg" style="width:100%; height:auto;">

</div>

## What is HTML?

**HTML (HyperText Markup Language)** is the standard markup language used to create and structure content on the World Wide Web.

- **HyperText** → Refers to text that links to other documents (via hyperlinks).
- **Markup Language** → Uses tags (like `<h1>`, `<p>`, `<a>`) to describe the structure and meaning of content.

👉 Think of HTML as the skeleton of a webpage — it defines what elements exist (headings, paragraphs, images, forms, buttons), but not how they look (that’s handled by CSS) or how they behave (that’s handled by JavaScript).

#### 🏗️ Basic Structure of an HTML Document
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <title>My First Page</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my first webpage.</p>
    <a href="https://example.com">Visit Example</a>
  </body>
</html>
```

#### 🚀 Why HTML is Important

- **🌍 Universal:** Every website uses it.
- **🏗️ Foundation:** Works with CSS (style) + JS (behavior).
- **📱 Responsive Web:** Works with frameworks like React, Angular, Vue.
- **♿ Accessibility:** Provides semantic meaning (like `<nav>`, `<header>`, `<footer>`) to help screen readers and SEO.


## 📄 HTML Document

#### ⚡ Basic Structure of an HTML Document

Every HTML page follows a standard skeleton (boilerplate).
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>My First HTML Page</title>
  </head>
  <body>
    <h1>Hello, World!</h1>
    <p>This is my first HTML page.</p>
  </body>
</html>
```

#### 🧱 Breakdown of Each Part

**1. `<!DOCTYPE html>`**

- Declares the document type and version of HTML.
- In modern web, always use:
```html
<!DOCTYPE html>
```
> → Tells the browser this is an HTML5 document.

**2. `<html>` Element**

- The root element of an HTML page.
- Wraps everything inside.
- Common attribute: `lang="en"` for accessibility and SEO.
```html
<html lang="en">
  ...
</html>
```

**3. `<head>` Section**

- Contains **metadata** (information about the page, not shown to users).
- Includes:
     - `<meta charset="UTF-8" />` → Sets character encoding to UTF-8 (supports most characters).
     - `<meta name="viewport" content="width=device-width, initial-scale=1.0" />` → Ensures proper scaling on mobile devices.
     - `<title>` → Sets the title shown in the browser tab.
     - `<link>` → For stylesheets, icons.
     - `<script>` → External JS can also go here.
Example:
```html
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Page</title>
  <link rel="stylesheet" href="styles.css" />
  <script src="script.js" defer></script>
</head>
```

**4. `<body>` Section**

- Contains visible content for users.
- Includes headings, paragraphs, images, links, buttons, forms, etc.

Example:
```html
<body>
  <h1>Welcome to My Website</h1>
  <p>This is a paragraph of text on my webpage.</p>
  <img src="image.jpg" alt="Description of image" />
  <a href="https://example.com">Visit Example</a>
</body>
```

**🎯 Real-World Example** 
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>TechCorp - Home</title>
    <link rel="stylesheet" href="styles.css" />
  </head>

  <body>
    <header>
      <h1>TechCorp</h1>
      <nav>
        <a href="/">Home</a>
        <a href="/services">Services</a>
        <a href="/contact">Contact</a>
      </nav>
    </header>

    <main>
      <h2>Welcome to TechCorp</h2>
      <p>We provide innovative tech solutions for businesses worldwide.</p>
    </main>

    <footer>
      <p>&copy; 2025 TechCorp. All rights reserved.</p>
    </footer>
  </body>
</html>
```

<div>

 <img src="https://i.ibb.co.com/b5QrZJSX/html-intro.png" style="width:100%; height:auto;">

</div>

### HTML Tag

A tag is the building block of HTML.

- Tags are keywords wrapped in angle brackets (`<>`).
- Most tags come in pairs: opening tag `<tagname>` and closing tag `</tagname>`.
- Some tags are self-closing (e.g., `<img />`, `<br />`, `<input />`).

#### ⚡ Categories of HTML Tags

**1. Basic Structure Tags**

These form the skeleton of every HTML document.

| Tag        | Description |
|------------|-------------|
| `<!DOCTYPE>` | Declares the document type (HTML5). |
| `<html>`   | Root element of an HTML document. |
| `<head>`   | Container for metadata, scripts, styles. |
| `<body>`   | Contains the visible page content. |

Example:
```html
<!DOCTYPE html>   <!-- Declares HTML5 document -->
<html lang="en">  <!-- Root element -->
  <head>          <!-- Metadata (not shown to user) -->
    <title>My Website</title>
  </head>
  <body>          <!-- Visible content -->
    <h1>Hello World</h1>
  </body>
</html>
```

**2. ✍️ Text & Headings**

Used for headings, paragraphs, bold, italic, etc.

| Tag        | Description |
|------------|-------------|
| `<h1>` … `<h6>` | Headings from largest (`<h1>`) to smallest (`<h6>`). |
| `<p>`      | Paragraph of text. |
| `<span>`   | Inline text container (no semantic meaning). |
| `<br>`     | Line break. |
| `<hr>`     | Horizontal rule (divider). |
| `<b>` / `<strong>` | Bold text (`<strong>` is semantic for importance). |
| `<i>` / `<em>` | Italic text (`<em>` is semantic for emphasis). |
| `<u>`      | Underlined text. |
| `<mark>`   | Highlighted text. |
| `<small>`  | Smaller text. |
| `<sup>`    | Superscript text. |
| `<sub>`    | Subscript text. |

Example:
```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<p>This is a <b>bold</b> and <i>italic</i> text.</p>
<u>Underlined text</u>
<small>Smaller text</small>
<mark>Highlighted text</mark>
```

> `<strong>` indicates that the text is of strong importance, providing semantic meaning, while `<b>` does not convey any extra importance.


> The effect on a normal webpage of the tags `<strong>`, `<b>`, `<em>`, and `<i>` is the same. `<b>` and `<i>` tags stand for bold and italic. These two tags only apply font styling, and the bold tag `<b>` just adds more ink to the text; these tags don't say anything about the text.

> Whereas, `<strong>` and `<em>` tags represent that the span of text is of strong importance or more importance and emphatic stress respectively than the rest of the text. These tags have semantic meaning.

**3. 🔗 Links & Navigation**

| Tag        | Description |
|------------|-------------|
| `<a>`      | Creates a hyperlink. |
| `<nav>`    | Defines navigation links section. |

Example:
```html
<a href="https://example.com" target="_blank">Visit Example</a>
<nav>
  <a href="/">Home</a> | <a href="/about">About</a>
</nav>
```


**4. 🖼️ Media & Graphics**

| Tag        | Description |
|------------|-------------|
| `<img>`    | Displays an image. |
| `<figure>` | Groups media content with caption. |
| `<figcaption>` | Caption for a `<figure>`. |
| `<audio>`  | Embeds audio content. |
| `<video>`  | Embeds video content. |
| `<source>` | Defines media file sources for `<audio>`/`<video>`. |
| `<canvas>` | Used for drawing graphics with JavaScript. |
| `<svg>`    | Scalable Vector Graphics container. |


Example:
```html
<img src="photo.jpg" alt="A photo" width="200" />
<audio controls>
  <source src="song.mp3" type="audio/mpeg" />
</audio>
<video width="320" height="240" controls>
  <source src="movie.mp4" type="video/mp4" />
</video>

<figure>
  <img src="image.png" alt="Example" />
  <figcaption>This is an image caption</figcaption>
</figure>

<canvas id="myCanvas"></canvas>
<svg width="100" height="100">
  <circle cx="50" cy="50" r="40" stroke="black" fill="red" />
</svg>
```

In `<img>` tag:
- `src`: Specifies the path to the image file.
- `alt`: Provides alternative text for the image, which is displayed if the image cannot be loaded.

In `<video>` tag:
- `controls`: Adds video controls like play, pause, and volume.
- `source`: Specifies the video file and its format.

> The `<figure>` tag specifies the self-contained content, like diagrams, images, code snippets, etc. `<figure>` tag is used to semantically organize the contents of an image like image, image caption, etc., whereas the `<img>` tag is used to embed the picture in the HTML5 document.

**5.📋 Lists**

| Tag        | Description |
|------------|-------------|
| `<ul>`     | Unordered list (bullets). |
| `<ol>`     | Ordered list (numbers). |
| `<li>`     | List item. |
| `<dl>`     | Description list. |
| `<dt>`     | Term in a description list. |
| `<dd>`     | Description of a term. |


Example:
```html
<ul>
  <li>Apple</li>
  <li>Banana</li>
</ul>

<ol>
  <li>Step One</li>
  <li>Step Two</li>
</ol>

<dl>
  <dt>HTML</dt>
  <dd>HyperText Markup Language</dd>
</dl>
```

**6. 📊 Tables**


| Tag        | Description |
|------------|-------------|
| `<table>`  | Defines a table. |
| `<tr>`     | Table row. |
| `<th>`     | Table header cell. |
| `<td>`     | Table data cell. |
| `<caption>` | Table caption. |
| `<thead>`  | Groups table header rows. |
| `<tbody>`  | Groups main body rows. |
| `<tfoot>`  | Groups footer rows. |

```html
<table>
  <caption>Sample Table</caption>
  <thead>
    <tr>
      <th>Name</th>
      <th>Age</th>
      <th>City</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>Alice</td>
      <td>30</td>
      <td>New York</td>
    </tr>
    <tr>
      <td>Bob</td>
      <td>25</td>
      <td>Los Angeles</td>
    </tr>
  </tbody>
  <tfoot>
    <tr>
      <td colspan="3">End of Table</td>
    </tr>
  </tfoot>
```


**7. 📝 Forms & Input**

| Tag        | Description |
|------------|-------------|
| `<form>`   | Defines a form for user input. |
| `<input>`  | Input field (text, checkbox, radio, etc.). |
| `<textarea>` | Multi-line text input. |
| `<button>` | Clickable button. |
| `<select>` | Drop-down list. |
| `<option>` | An option in a drop-down list. |
| `<label>`  | Label for form input. |
| `<fieldset>` | Groups related form inputs. |
| `<legend>` | Caption for a `<fieldset>`. |
| `<datalist>` | Provides predefined input options. |
| `<output>` | Displays calculation/result of form. |


```html
<form action="/submit" method="POST">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username" />
  
  <label for="password">Password:</label>
  <input type="password" id="password" name="password" />
  
  <input type="checkbox" id="subscribe" /> Subscribe
  <input type="radio" name="gender" value="male" /> Male
  
  <select>
    <option>USA</option>
    <option>UK</option>
  </select>
  
  <textarea rows="4" cols="30">Write here...</textarea>
  
  <button type="submit">Submit</button>
</form>
```


**8. 🏗️ Semantic HTML5**

These give meaning to structure.

| Tag        | Description |
|------------|-------------|
| `<header>` | Introductory content or navigation. |
| `<nav>`    | Navigation links. |
| `<main>`   | Main page content. |
| `<section>` | A section of content. |
| `<article>` | Independent piece of content (e.g., blog post). |
| `<aside>`  | Sidebar or related content. |
| `<footer>` | Footer content. |
| `<address>` | Contact information. |

Example:
```html
<header>Site Header</header>
<nav>Navigation Links</nav>
<main>Main Content</main>
<article>Blog Post</article>
<section>Section of Content</section>
<aside>Sidebar Content</aside>
<footer>Site Footer</footer>
```

> Semantic HTML elements clearly describe their meaning in a human- and machine-readable way.

> As HTML5 was all about better semantics and arrangements of the tags and elements, the `<header>` tag specifies the header section of the webpage. Unlike in previous version there was one `<h1>` element for the entire webpage, now this is the header for one section such as `<article>` or `<section>`. According to the HTML5 specification, each <header> element must at least have one `<h1>` tag.


**9. ⚙️ Metadata & Scripting**

| Tag        | Description |
|------------|-------------|
| `<title>`  | Document title (appears in browser tab). |
| `<meta>`   | Metadata (charset, description, viewport, etc.). |
| `<link>`   | Links external resources (CSS, favicon). |
| `<style>`  | Internal CSS styles. |
| `<script>` | JavaScript code or external file reference. |
| `<noscript>` | Fallback content if JavaScript is disabled. |

```html
<script>
  console.log("Hello, world!");
</script>

<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Document</title>
</head>
<body>
```

**10. 🎛️ Interactive Elements**

| Tag        | Description |
|------------|-------------|
| `<details>` | Collapsible content. |
| `<summary>` | Summary/label for `<details>`. |
| `<dialog>` | Dialog box or popup window. |
| `<progress>` | Progress bar. |
| `<meter>`   | Measurement within a known range. |
| `<time>`    | Represents a time or date. |

Example:
```html
<details>
  <summary>More Info</summary>
  <p>Details here...</p>
</details>
```

### HTML Element

An element is a complete unit in HTML, consisting of a start tag, content, and an end tag.

Example:
```html
<p>This is a paragraph.</p>
```
- `<p>` is the start tag.
- `This is a paragraph.` is the content.
- `</p>` is the end tag.

> 👉 So: Tag = label, Element = complete structure.

**Block-level elements**

Block-level elements start on a new line and take up the full width available. Block-level elements are the building blocks of page layout. Examples include: `<p>`, `<div>`, `<section>`, `<article>`, `<nav>`, `<header>`, `<footer>`.

**Inline elements**

Inline elements do not start on a new line and only take up as much width as necessary. Inline elements are typically used for small pieces of content within block-level elements. Examples include: `<span>`, `<a>`, `<strong>`, `<em>`, `<img>`.

**HTML element editable in the browser**

To make an HTML element editable directly in the browser, you can set the contenteditable attribute to true. This allows users to edit the content of the element in place.
Example:
```html
<div contenteditable="true">
  This is an editable div. Click here to edit the text.
</div>
```

### HTML Attributes

Attributes provide additional information about HTML elements.

- Always included in the opening tag.
- Consist of a name and a value, separated by an equals sign.
- Values are enclosed in quotes (single or double).
- They are written as `name="value"`.

Example:
```html
<a href="https://example.com" target="_blank" rel="noopener">Visit Example</a>
```
Here:
- `href` is an attribute specifying the link's destination.
- `target="_blank"` opens the link in a new tab.
- `rel="noopener"` improves security when using `_blank`.

Common attributes:
- `id` → Unique identifier.
- `class` → Class name(s) for CSS/JS.
- `src` → Source URL for images, scripts.
- `alt` → Alternative text for images.
- `title` → Tooltip text.
- `style` → Inline CSS styles.

✅ Example:
```html
<a href="https://example.com" target="_blank" rel="noopener">Visit Example</a>
```

> Multiple elements in HTML can have the same class value, whereas a value of id attribute of one element cannot be associated with another HTML element.

### HTML Comments

- Used to add notes or explanations in the code.
- Not displayed in the browser.
- Start with `<!--` and end with `-->`.

Example:
```html
<!-- This is a comment -->
```

### Hyperlink in HTML

A hyperlink is created using the `<a>` tag (anchor tag).

Syntax:
```html
<a href="URL">Link Text</a>
```

- `href` → (hypertext reference) defines the destination URL.
- The text (or image) between `<a>` and `</a>` is clickable.

#### ⚡ Common Attributes of Hyperlinks

**1. target**

Controls how the link opens.
```html
<a href="https://example.com" target="_blank">Open in new tab</a>
```

- `_self` → default (opens in same tab).
- `_blank` → opens in a new tab.

**2. rel**

Specifies the relationship between the current document and the linked document.
```html
<a href="https://example.com" rel="noopener">Secure link</a>
```
- `noopener` → prevents the linked document from accessing the opener window.
- `noreferrer` → prevents the browser from sending the referring page's URL.

**3. download**

Indicates that the link is for downloading a resource.
```html
<a href="file.pdf" download>Download PDF</a>
```

- `download` → prompts the user to save the linked URL instead of navigating to it.

**4. title**

Tooltip when hovering over the link.
```html
<a href="https://example.com" title="Visit Example">Example</a>
```

**5. Linking to a Section on the Same Page**

To link to a specific section within the same page, use the `href` attribute with a hash (`#`) followed by the section's `id`.

Example:
```html
<a href="#section1">Go to Section 1</a>

<section id="section1">
  <h2>Section 1</h2>
  <p>Content of section 1.</p>
</section>
```

**6. Email & Phone Links**

**Email Links**

Use the `mailto:` scheme in the `href` attribute to create an email link.

Example:
```html
<a href="mailto:example@example.com">Send Email</a>
```

**Phone Links**

Use the `tel:` scheme in the `href` attribute to create a phone link.

Example:
```html
<a href="tel:+1234567890">Call Us</a>
```

**7. Using Images as Links**

To use an image as a link, place an `<img>` tag inside an `<a>` tag.

Example:
```html
<a href="https://example.com">
  <img src="image.jpg" alt="Example Image">
</a>
```

### Specify multiple language versions of a webpage

To specify multiple language versions of a webpage, use the `hreflang` attribute in the `<link>` tag within the `<head>` section.

Example:
```html
<link rel="alternate" href="https://example.com/en" hreflang="en" />
<link rel="alternate" href="https://example.com/es" hreflang="es" />
```


## HTML Entities

An HTML Entity is a special code that represents a character that either:

1. Cannot be typed directly on the keyboard, OR
2. Has a reserved meaning in HTML (like `<`, `>`, `&`).
3. They always start with an ampersand (`&`) and end with a semicolon (`;`).

#### 🔑 Commonly Used HTML Entities

**✅ Reserved Characters**

| Entity | Symbol | Description |
|--------|--------|-------------|
| `&lt;` | < | Less than |
| `&gt;` | > | Greater than |
| `&amp;` | & | Ampersand |
| `&quot;` | " | Double quote |
| `&apos;` | ' | Apostrophe / Single quote |
| `&nbsp;` |   | Non-breaking space |

Example:
```html
<p>This is a &lt;strong&gt;example&lt;/strong&gt;.</p>
<p>This is a &quot;double&quot; quote.</p>
<p>This is a &apos;single&apos; quote.</p>
```

**Output:**
This is a <strong>example</strong>.
This is a "double" quote.
This is a 'single' quote.


**📖 Punctuation & Symbols**

| Entity | Symbol | Description |
|--------|--------|-------------|
| `&copy;` | © | Copyright |
| `&reg;` | ® | Registered trademark |
| `&trade;` | ™ | Trademark |
| `&cent;` | ¢ | Cent |
| `&pound;` | £ | Pound Sterling |
| `&yen;` | ¥ | Yen |
| `&euro;` | € | Euro |
| `&sect;` | § | Section |
| `&para;` | ¶ | Paragraph |
| `&bull;` | • | Bullet |
| `&hellip;` | … | Ellipsis |
| `&ndash;` | – | En dash |
| `&mdash;` | — | Em dash |
| `&prime;` | ′ | Prime (minutes/feet) |
| `&Prime;` | ″ | Double prime (seconds/inches) |

Example:
```html
<p>&copy; 2024 My Company</p>
<p>Price: &euro;100</p>
<p>Example: &hellip;</p>
<p>&copy; 2025 TechCorp. All rights reserved. &reg; Trademark Protected.</p>
```
**Output:**
© 2024 My Company
Price: €100
Example: …
© 2025 TechCorp. All rights reserved. ® Trademark Protected.


**🔢 Mathematical Symbols**

| Entity | Symbol | Description |
|--------|--------|-------------|
| `&plus;` | + | Plus |
| `&minus;` | − | Minus |
| `&times;` | × | Multiplication |
| `&divide;` | ÷ | Division |
| `&equals;` | = | Equals |
| `&ne;` | ≠ | Not equal |
| `&le;` | ≤ | Less than or equal |
| `&ge;` | ≥ | Greater than or equal |
| `&radic;` | √ | Square root |
| `&sum;` | ∑ | Summation |
| `&infin;` | ∞ | Infinity |
| `&pi;` | π | Pi |
| `&deg;` | ° | Degree |

Example:
```html
<p>5 &plus; 3 &equals; 8</p>
<p>Area = &pi; r&sup2;</p>
<p>Square root of 16 is &radic;16 = 4</p>
<p>Infinity symbol: &infin;</p>
```

**Output:**
5 + 3 = 8
Area = π r²
Square root of 16 is √16 = 4
Infinity symbol: ∞


**⬆️ Arrows**

| Entity | Symbol | Description |
|--------|--------|-------------|
| `&larr;` | ← | Left arrow |
| `&uarr;` | ↑ | Up arrow |
| `&rarr;` | → | Right arrow |
| `&darr;` | ↓ | Down arrow |
| `&harr;` | ↔ | Left-right arrow |
| `&crarr;` | ↵ | Carriage return arrow |

Example:
```html
<p>Go back &larr;</p>
<p>Scroll up &uarr;</p>
<p>Next &rarr;</p>
<p>Scroll down &darr;</p>
<p>Move &harr;</p>
<p>Enter &crarr;</p>
```
**Output:**
Go back ←
Scroll up ↑
Next →
`<p>Scroll down ↓</p>`
Move ↔
Enter ↵


**♡ Shapes & Misc**

| Entity | Symbol | Description |
|--------|--------|-------------|
| `&hearts;` | ♥ | Heart |
| `&clubs;` | ♣ | Club |
| `&diams;` | ♦ | Diamond |
| `&spades;` | ♠ | Spade |
| `&starf;` | ★ | Solid star |
| `&phone;` | ☎ | Telephone |
| `&check;` | ✓ | Check mark |
| `&cross;` | ✗ | Cross mark |
| `&music;` | ♫ | Music note |
| `&sun;` | ☀ | Sun symbol |

Example:
```html
<p>I &hearts; HTML</p>
<p>Solid star: &starf;</p>
<p>Check mark: &check;</p>
<p>Music note: &music;</p>
<p>Phone symbol: &phone;</p>
<p>Sun symbol: &sun;</p>
```

**Output:**
I ♥ HTML
Solid star: ★
Check mark: ✓
Music note: ♫
Phone symbol: ☎
Sun symbol: ☀


## Web Storage in HTML5

Web Storage is a mechanism introduced in HTML5 that allows websites to store data in the browser (on the client side) more efficiently than cookies.

It provides two main storage types:

**1. localStorage** → Stores data with no expiration date (persists even after browser is closed).
**2. sessionStorage** → Stores data for a single session (cleared when the browser tab is closed).

#### 🔑 Why Web Storage Instead of Cookies?

| Feature          | Cookies                     | Web Storage                |
|------------------|-----------------------------|----------------------------|
| **Storage Limit** | 4KB per domain (limited)   | 5MB per domain (unlimited) |
| **Data Type**     | Limited to strings         | Supports various types     |
| **Security**      | Not encrypted by default    | Encrypted by default       |
| **Access**        | HTTP-only (not accessible) | Accessible by JavaScript   |
| **API**          |  Complex        | Rich API for manipulation  |
| **Lifetime**     | Configurable | Persistent or session-based |


#### 🛠️ The Two Types of Web Storage

**1. localStorage**

- Stores data permanently (until manually cleared).
- Shared across all tabs/windows of the same origin.

Example (localStorage):
```javascript
// Store data
localStorage.setItem('username', 'JohnDoe');
localStorage.setItem('age', '30');
// Retrieve data
const username = localStorage.getItem('username'); // "JohnDoe"
const age = localStorage.getItem('age'); // "30"
// Remove data
localStorage.removeItem('age');
// Clear all data
localStorage.clear();
```

**2. sessionStorage**

- Stores data per session (cleared when tab is closed).
- Data is NOT shared between different browser tabs/windows.

Example (sessionStorage):
```javascript
// Store data
sessionStorage.setItem('key', 'value');

// Retrieve data
const data = sessionStorage.getItem('key');

// Remove data
sessionStorage.removeItem('key');

// Clear all data
sessionStorage.clear();
```

#### 🔑 Common Web Storage Methods

| Method            | Description                          |
|-------------------|------------------------------------|
| `setItem(key, value)` | Stores a key-value pair            |
| `getItem(key)`       | Retrieves the value for a key      |
| `removeItem(key)`    | Removes a key-value pair            |
| `clear()`            | Clears all key-value pairs          |
| `key(index)`         | Returns the key at the specified index |
| `length`             | Returns the number of stored items  |

#### 📦 Common Web Storage Objects
| Object          | Description                        |
|-----------------|------------------------------------|
| `localStorage`  | Stores data permanently            |
| `sessionStorage`| Stores data per session            |
| `Cookie`        | Stores data in HTTP-only cookies    |


## New Input Types Provided by HTML5 for Forms

HTML5 introduced several new input types to enhance form functionality and user experience. These new input types provide built-in validation, better user interfaces, and improved data handling.

| Input Type      | Description                                      | Example Usage                                   |
|-----------------|--------------------------------------------------|------------------------------------------------|
| `email`         | For email addresses, with built-in validation.   | `<input type="email" name="user_email" />`     |
| `url`           | For URLs, with built-in validation.              | `<input type="url" name="website" />`          |
| `tel`           | For telephone numbers.                           | `<input type="tel" name="phone" />`             |
| `number`        | For numeric input, with min, max, step attributes.| `<  input type="number" name="quantity" min="1" max="10" step="1" />` |
| `range`         | For selecting a value from a range (slider).     | `<input type="range" name="volume" min="0" max="100" />` |
| `date`          | For selecting a date (calendar picker).          | `<input type="date" name="birthday" />`            |
| `time`          | For selecting a time (time picker).              | `<input type="time" name="appointment_time" />` |
| `datetime-local`| For selecting a date and time (local).           | `<input type="datetime-local" name="meeting" />` |
| `color`         | For selecting a color (color picker).            | `<input type="color" name="favcolor" />`          |
| `search`        | For search queries, with optimized UI.           | `<input type="search" name="search" />`            |
| `file`          | For file uploads, allowing multiple files.       | `<input type="file" name="upload" multiple />` |
| `checkbox`      | For selecting multiple options.                  | `<input type="checkbox" name="subscribe" />`     |
| `radio`         | For selecting one option from a set.             | `<input type="radio" name="gender" value="male" />` |
| `button`        | For custom buttons.                              | `<button type="button" onclick="myFunction()">Click Me</button>` |
| `submit`        | For submitting a form.                           | `<input type="submit" value="Submit" />`         |
| `reset`         | For resetting a form to its initial values.     | `<input type="reset" value="Reset" />`            |
| `image`         | For submitting a form with an image.             | `<input type="image" src="image.jpg" alt="Submit" />` |
| `hidden`        | For hidden form fields.                          | `<input type="hidden" name="user_id" value="12345" />` |
| `password`      | For password input (masked).                     | `<input type="password" name="user_password" />`  |
| `text`          | For single-line text input.                      | `<input type="text" name="username" />`          |
| `textarea`      | For multi-line text input.                       | `<textarea name="message" rows="4" cols="50"></textarea>` |
| `select`        | For drop-down lists.                            | `<select name="country"><option value="us">USA</option></select>` |
| `datalist`      | For predefined options in an input field.        | `<input list="browsers" name="browser" /><datalist id="browsers"><option value="Chrome"><option value="Firefox"></datalist>` |
| `output`        | For displaying the result of a calculation.      | `<output name="result" for="a b">0</output>`     |
| `fieldset`      | For grouping related form elements.              | `<fieldset><legend>Personal Info</legend><input type="text" name="name" /></fieldset>` |
| `legend`        | For providing a caption for a `<fieldset>`.      | `<fieldset><legend>Personal Info</legend></fieldset>` |

Example Form Using New Input Types:
```html
    <form>  
        <div>
            <label>Date:</label>
            <input type="date" id="date" />
            <br>
            <label>Week:</label>
            <input type="week" id="week" />
            <br>
            <label>Month:</label>
            <input type="month" id="month" />
            <br>
            <label>Time:</label>
            <input type="time" id="time" />
            <br>
            <label>Datetime:</label>
            <input type="datetime" id="datetime" />
            <br>
            <label>Datetime Local:</label>
            <input type="datetime-local" id="datetime-local" />
            <br>
            <label>Color:</label>
            <input type="color" id="color"/>
            <br>
            <label>Email:</label>
            <input type="email" id="email" placeholder="email address" />
            <br>
            <label>Number:</label>
            <input type="number" id="number" />
            <br>
            <label>Search:</label>
            <input type="search" id="search" />
            <br>
            <label>Phone:</label>
            <input type="tel" id="phone" placeholder="Phone Number" pattern="\d{10}$" />
            <br>
            <label>Range:</label>
            <input type="range" id="range" />
            <br>
            <label>URL:</label>
            <input type="url" id="url"/>
        </div>  
    </form>
```


## New tags in Media Elements in HTML5

HTML5 introduced new media elements to handle audio and video content natively in web browsers without the need for external plugins like Flash. The two primary media elements are `<audio>` and `<video>`. Additionally, the `<source>` element is used to specify multiple media sources for these elements.

| Tag        | Description                                      | Example Usage                                   |
|------------|--------------------------------------------------|------------------------------------------------|
| `<audio>`  | Defines an audio element to play audio content. | `<audio controls> <source src="audio.mp3"> </audio>` |
| `<video>`  | Defines a video element to play video content.   | `<video controls> <source src="video.mp4"> </video>` |
| `<source>` | Specifies the media source for audio or video.   | `<source src="audio.mp3" type="audio/mpeg">`    |
| `<track>`  | Adds text tracks (subtitles, captions) to media. | `<track kind="subtitles" src="subs.vtt" srclang="en" label="English">` |
| `<embed>`  | Embeds external content (like Flash, PDF).        | `<embed src="file.swf" width="400" height="300">` |
| `<object>` | Embeds multimedia content (like images, videos).  | `<object data="file.pdf" type="application/pdf" width="400" height="300"></object>` |
| `<param>`  | Defines parameters for `<object>`.                | `<param name="autoplay" value="true">`          |
| `<canvas>` | Used for drawing graphics via scripting (usually JavaScript). | `<canvas id="myCanvas" width="200" height="100"></canvas>` |
| `<svg>`    | Defines Scalable Vector Graphics.                 | `<svg width="100" height="100"><circle cx="50" cy="50" r="40" stroke="black" fill="red"/></svg>` |
| `<map>`    | Defines an image map (clickable areas on an image). | `<map name="image-map"><area shape="rect" coords="34,44,270,350" href="link.html"></map>` |
| `<area>`   | Defines a clickable area within an image map.     | `<area shape="circle" coords="100,100,50" href="link.html">` |
| `<bdi>`    | Isolates a part of text that might be formatted in a different direction. | `<bdi>Some text</bdi>` |

Example:
```html
<label>
       Video:
   </label>
    <video width="320" height="240" controls>
        <source src="video.mp4" type="video/mp4">
        <track src="subtitles.vtt" kind="subtitles" srclang="en" label="English">
    </video>
    <br>
    <label>
        Embed:
    </label>
    <embed type="video/webm" src="https://www.youtube.com/embed/MpoE6s2psCw" width="400" height="300">
    <br>
    <label>
        Audio:
    </label>
    <audio controls>
        <source src="audio.mp3" type="audio/mpeg">
    </audio>
```



<div align="center" style="margin-top: 40px; margin-bottom: 40px;">
  <h1>CSS3</h1>
</div>


## What is CSS?

CSS (Cascading Style Sheets) is a stylesheet language used to describe the presentation and formatting of a document written in HTML or XML. It allows you to control the layout, colors, fonts, spacing, and overall visual appearance of web pages.

#### ✨ Key Features of CSS

**1. Separation of Concerns**

- HTML handles content
- CSS handles presentation (design/layout)

**2. Cascading**

- Styles are applied in a hierarchy (browser default → external CSS → inline CSS).

**3. Reusability**

- One CSS file can style multiple web pages.

**4. Responsive Design**

- CSS allows different layouts for different devices (desktop, tablet, mobile).

**5. Consistency**

- Makes your website look uniform across all pages.


#### Why use CSS?

- **Improved Design**: CSS provides powerful tools to create visually appealing web pages.
- **Faster Load Times**: External CSS files can be cached by browsers, reducing load times.
- **Easier Maintenance**: Changes can be made in one place (CSS file) rather than in multiple HTML files.
- **Accessibility**: CSS can enhance the accessibility of web content for users with disabilities.


Example:
```css
body {
  font-family: Arial, sans-serif;
  background-color: #f0f0f0;
  color: #333;
}
h1 {
  color: #007BFF;
}
```

#### 🔑 CSS Syntax

```css
selector {
  property: value;
}
```
- **Selector**: HTML element(s) to be styled (e.g., `body`, `h1`, `.class`, `#id`).
- **Property**: CSS property to be changed (e.g., `color`, `font-size`).
- **Value**: The value assigned to the property (e.g., `red`, `16px`).

Example:
```css
/* Universal selector */
* {
  box-sizing: border-box;
}

/* Single Selector */
h1 {
  color: blue;
  font-size: 24px;
}

/* Multiple Selectors */
h1, h2, h3 {
  font-family: Arial, sans-serif;
  color: darkblue;
}

/* Class selector */
.card {
  border: 1px solid #ddd;
  padding: 20px;
}

/* ID selector */
#main-title {
  font-size: 32px;
  text-align: center;
}

/* Descendant selector */
nav a {
  text-decoration: none;
  color: black;
}

/* Child selector */
ul > li {
  list-style-type: square;
}

/* Adjacent sibling selector */
p + p {
  margin-top: 10px;
}

/* General sibling selector */
h2 ~ p {
  color: gray;
}

/* Attribute selector */
input[type="text"] {
  border: 1px solid #ccc;
  padding: 5px;
}

/* Pseudo-class selector */
a:hover {
  color: red;
}

/* Pseudo-element selector */
p::first-letter {
  font-size: 200%;
  color: green;
}

/* Pseudo-class and pseudo-element selectors */
input:focus::placeholder {
  color: blue;
}
```
- `.card` → applies to all elements with `class="card"`.
- `#main-title` → applies only to element with `id="main-title"`.

#### 🔗 Ways to Apply CSS

1. **Inline CSS**: Apply styles directly to an HTML element using the `style` attribute.

```html
   <h1 style="color: blue; font-size: 24px;">Hello World</h1>
```

2. **Internal CSS**: Define styles within a `<style>` tag in the `<head>` section of an HTML document.

```html
   <head>
       <style>
           h1 {
               color: blue;
               font-size: 24px;
           }
       </style>
   </head>
```

3. **External CSS**: Link to an external CSS file using the `<link>` tag.
```html
  <head>
       <link rel="stylesheet" type="text/css" href="styles.css">
  </head>
```
4. **CSS in JavaScript**: Dynamically apply styles using JavaScript.

```javascript
   document.getElementById("myElement").style.color = "blue";
```

5. **CSS Preprocessors**: Use tools like SASS or LESS to write more advanced CSS with variables, nesting, and functions, which then compile to standard CSS.

```scss
    $primary-color: blue;
  
    h1 {
        color: $primary-color;
        font-size: 24px;
    }
```

6. **CSS-in-JS**: Use libraries like styled-components or Emotion to write CSS directly within JavaScript files, often used in React applications.

```javascript
    import styled from 'styled-components';
    const Title = styled.h1`
        color: blue;
        font-size: 24px;
    `;
```

7. **CSS Modules**: A CSS file in which all class and animation names are scoped locally by default. Commonly used in React projects.

```css
    /* styles.module.css */
    .title {
        color: blue;
        font-size: 24px;
    }
    ```
    ```javascript
    import styles from './styles.module.css';
    <h1 className={styles.title}>Hello World</h1>
```

Example:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CSS Example</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        p {
            color: green;
        }
    </style>
</head>
<body>
    <h1 style="color: blue;">Hello World</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```
```css
/* styles.css */
body {
    font-family: Arial, sans-serif;
    background-color: #f0f0f0;
    color: #333;
}
h1 {
    font-size: 24px;
}
```

8. **CSS Frameworks**: Use pre-designed CSS frameworks like Bootstrap, Tailwind CSS, or Foundation to quickly build responsive and visually appealing web pages with pre-defined styles and components.

```html
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css">
    <button class="btn btn-primary">Bootstrap Button</button>
```

9. **CSS Variables (Custom Properties)**: Define reusable values in CSS using variables, which can be used throughout the stylesheet.

```css
    /* styles.css */
    :root {
        --primary-color: #007bff;
        --secondary-color: #6c757d;
    }
    body {
        background-color: var(--primary-color);
        color: var(--secondary-color);
    }
```


- As Inline has the highest priority, any styles that are defined in the internal and external style sheets are overridden by Inline styles.
- Internal or Embedded stands second in the priority list and overrides the styles in the external style sheet.
- External style sheets have the least priority. If there are no styles defined either in the inline or internal style sheet then external style sheet rules are applied for the HTML tags.


#### CSS Box Model
The CSS Box Model is a fundamental concept in web design that describes how elements are structured and how their dimensions are calculated. Every HTML element can be considered as a rectangular box, which consists of several layers: content, padding, border, and margin.
```css
/* Example of Box Model properties */
.box {
  width: 200px; /* Content width */
  height: 100px; /* Content height */
  padding: 20px; /* Space between content and border */
  border: 5px solid black; /* Border thickness and style */
  margin: 10px; /* Space outside the border */
}
```

#### Add a comment in CSS
Comments in CSS are used to add notes or explanations within the stylesheet. They are ignored by the browser and do not affect the rendering of the page. Comments can be helpful for documenting code, explaining complex sections, or temporarily disabling code during development.
```css
/* This is a single-line comment in CSS */
/*
    This is a multi-line comment in CSS.
    It can span multiple lines.
*/
body {
  font-family: Arial, sans-serif; /* Setting the font family */
  background-color: #f0f0f0; /* Light gray background */
  color: #333; /* Dark gray text color */
  /* The following line sets the margin for the body */
  margin: 0; /* Remove default margin */
  padding: 0; /* Remove default padding */
  /* Box-sizing property to include padding and border in the element's total width and height */
  box-sizing: border-box;
}
h1 {
  color: #007BFF; /* Blue color for headings */
}
```

#### `rgba()` in CSS

The `rgba()` function in CSS is used to define colors using the Red-Green-Blue (RGB) color model along with an Alpha channel for transparency. The `rgba()` function allows you to specify colors with varying levels of opacity, making it useful for creating overlays, backgrounds, and other design elements that require transparency.

**`rgba` stands for:**

- R = Red
- G = Green
- B = Blue
- A = Alpha (opacity / transparency level)

It’s an extension of the regular RGB color model, with an added alpha channel that controls transparency.

**🛠️ Syntax**
```css
rgba(red, green, blue, alpha)
```
- `red`, `green`, `blue`: Integer values from 0 to 255 representing the intensity of each color component.
- `alpha`: A decimal value between 0 (fully transparent) and 1 (fully opaque) representing the opacity level.


✅ Examples:
```css
/* Example 1: Full opacity (100% visible) */
background-color: rgba(255, 0, 0, 1); /* Red color */
/* Example 2: 50% opacity */
background-color: rgba(0, 255, 0, 0.5); /* Green color with 50% transparency */
/* Example 3: 25% opacity */
background-color: rgba(0, 0, 255, 0.25); /* Blue color with 25% transparency */
/* Example 4: Semi-transparent black */
background-color: rgba(0, 0, 0, 0.7); /* Black with 70% opacity */
/* Example 5: Semi-transparent white */
background-color: rgba(255, 255, 255, 0.3); /* White with 30% opacity */
```

#### `opacity` in CSS
The `opacity` property in CSS is used to set the transparency level of an element, including its content and background. It affects the entire element, making it more or less transparent based on the specified value.
**🛠️ Syntax**
```css
opacity: value;
```
- `value`: A decimal value between 0 (fully transparent) and 1 (fully opaque).

✅ Examples:
```css
/* Example 1: Fully opaque (100% visible) */
opacity: 1; /* No transparency */
/* Example 2: 75% opacity */
opacity: 0.75; /* 25% transparent */
/* Example 3: 50% opacity */
opacity: 0.5; /* 50% transparent */
/* Example 4: 25% opacity */
opacity: 0.25; /* 75% transparent */
/* Example 5: Fully transparent (0% visible) */
opacity: 0; /* Completely invisible */
```


#### CSS Units
CSS units are used to specify the size, length, or measurement of various properties in CSS. They can be broadly categorized into two types: absolute units and relative units.
**1. Absolute Units**
Absolute units are fixed and do not change based on other elements or the viewport size. They are best used for print or when you need precise control over the size of an element.
| Unit | Description               | Example Usage          |
|------|---------------------------|------------------------|
| `px` | Pixels                    | `width: 100px;`        |
| `pt` | Points (1pt = 1/72 inch)  | `font-size: 12pt;`      |
| `cm` | Centimeters               | `margin: 2cm;`         |
| `mm` | Millimeters               | `padding: 10mm;`       |
| `in` | Inches                    | `border: 1in solid;`   |

**2. Relative Units**
Relative units are based on other elements or the viewport size, making them more flexible and adaptable to different screen sizes and resolutions.
| Unit | Description                               | Example Usage               |
|------|-------------------------------------------|-----------------------------|
| `%`  | Percentage of the parent element's size   | `width: 50%;`             |
| `em` | Relative to the font-size of the element  | `font-size: 2em;` (2 times the current font size) |
| `rem`| Relative to the font-size of the root element | `font-size: 1.5rem;` (1.5 times the root font size) |
| `vw` | Viewport width (1% of the viewport's width) | `width: 10vw;`            |
| `vh` | Viewport height (1% of the viewport's height) | `height: 10vh;`          |
| `vmin`| Minimum of `vw` and `vh`                  | `font-size: 5vmin;`          |
| `vmax`| Maximum of `vw` and `vh`                  | `font-size: 5vmax;`          |

✅ Examples:
```css
/* Absolute Units */
.box {
  width: 200px; /* Fixed width */
  height: 100px; /* Fixed height */
  margin: 10mm; /* Margin in millimeters */
}
.text {
  font-size: 16pt; /* Font size in points */
}
```
```css
/* Relative Units */
.container {
  width: 80%; /* 80% of the parent element's width */
  padding: 2em; /* Padding relative to the element's font size */
}
.title {
  font-size: 2rem; /* Font size relative to the root element's font size */
}
.responsive-box {
  width: 50vw; /* 50% of the viewport's width */
  height: 30vh; /* 30% of the viewport's height */
}
```

#### HSLA in CSS
The `hsla()` function in CSS is used to define colors using the Hue-Saturation-Lightness (HSL) color model along with an Alpha channel for transparency. The `hsla()` function allows you to specify colors in a way that is often more intuitive than the traditional RGB model, especially when it comes to adjusting color properties like saturation and lightness.
**`hsla` stands for:**
- H = Hue
- S = Saturation
- L = Lightness
- A = Alpha (opacity / transparency level)
It’s an extension of the regular HSL color model, with an added alpha channel that controls transparency.
**🛠️ Syntax**
```css
hsla(hue, saturation, lightness, alpha)
```
- `hue`: An integer value from 0 to 360 representing the color's position on the color wheel (0 = red, 120 = green, 240 = blue).
- `saturation`: A percentage value (0% to 100%) representing the intensity of the color (0% = gray, 100% = full color).
- `lightness`: A percentage value (0% to 100%) representing the brightness of the color (0% = black, 100% = white).
- `alpha`: A decimal value between 0 (fully transparent) and 1 (fully opaque) representing the opacity level.

✅ Examples:
```css
/* Example 1: Full opacity (100% visible) */
background-color: hsla(0, 100%, 50%, 1); /* Red color */
/* Example 2: 50% opacity */
background-color: hsla(120, 100%, 50%, 0.5); /* Green color with 50% transparency */
/* Example 3: 25% opacity */
background-color: hsla(240, 100%, 50%, 0.25); /* Blue color with 25% transparency */
/* Example 4: Semi-transparent black */
background-color: hsla(0, 0%, 0%, 0.7); /* Black with 70% opacity */
/* Example 5: Semi-transparent white */
background-color: hsla(0, 0%, 100%, 0.3); /* White with 30% opacity */
```


### CSS backgrounds properties

In CSS, the background is the "layer" behind the content and padding of an element. You can style it using different background properties.

#### 🛠️ CSS Background Properties

**1. `background-color`**

Sets the background color.
```css
body {
  background-color: lightblue;
}
```

**2. `background-image`**

Sets a background image.
```css
div {
  background-image: url('background.jpg');
}
```

**3. `background-repeat`**

Controls whether the background image repeats.

- Values: `repeat` (default), `repeat-x`, `repeat-y`, `no-repeat`.
```css
div {
  background-image: url('background.jpg');
  background-repeat: no-repeat;
}
```

**4. `background-position`**

Sets the starting position of the background image.
- Values: `left`, `right`, `center`, `top`, `bottom`, or specific coordinates (e.g., `50% 50%`).
```css
div {
  background-image: url('background.jpg');
  background-position: top right;
}
```

**5. `background-size`**

Specifies the size of the background image.
- Values: `auto` (default), `cover`, `contain`, or specific dimensions (e.g., `100px 200px`).
```css
div {
  background-image: url('background.jpg');
  background-size: cover;
}
```

**6. `background-attachment`**

Controls whether the background image scrolls with the page or is fixed.
- Values: `scroll` (default), `fixed`, `local`.
```css
div {
  background-image: url('background.jpg');
  background-attachment: fixed;
}
```

**7. `background-clip`**

Defines how far the background extends within an element.
- Values: `border-box` (default), `padding-box`, `content-box`.
```css
div {
  background-color: lightblue;
  background-clip: padding-box;
}
```

**8. `background-origin`**

Specifies the positioning area of the background image.
- Values: `border-box` (default), `padding-box`, `content-box`.
```css
div {
  background-image: url('background.jpg');
  background-origin: content-box;
}
```

**9. `background` (shorthand property)**

Combines all background properties into one declaration.
```css
div {
  background: lightblue url('background.jpg') no-repeat top right / cover fixed;
}
```



### CSS border properties

In CSS, borders are used to define the edges of an element. You can customize the appearance of borders using various border properties.

#### 🛠️ CSS Border Properties

**1. `border-width`**

Sets the width of the border.
- Values: `thin`, `medium` (default), `thick`, or specific measurements (e.g., `2px`, `0.5em`).
```css
div {
  border-width: 2px;
}
```

**2. `border-style`**

Sets the style of the border.
- Values: `none` (default), `solid`, `dashed`, `dotted`, `double`, `groove`, `ridge`, `inset`, `outset`.
```css
div {
  border-style: solid;
}
```

**3. `border-color`**

Sets the color of the border.
- Values: color names, hex codes, RGB, RGBA, HSL, HSLA.
```css
div {
  border-color: red;
}
```

**4. `border` (shorthand property)**

Combines `border-width`, `border-style`, and `border-color` into one declaration.
```css
div {
  border: 2px solid red;
}
```

**5. `border-top`, `border-right`, `border-bottom`, `border-left`**

Sets the border properties for individual sides of an element.
```css
div {
  border-top: 2px solid red;
  border-right: 2px dashed blue;
  border-bottom: 2px dotted green;
  border-left: 2px double black;
}
```

**6. `border-radius`**

Sets the rounded corners of the border.
- Values: specific measurements (e.g., `5px`, `50%` for a circle).
```css
div {
  border: 2px solid red;
  border-radius: 10px;
}
```

**7. `border-image`**

Sets an image as the border of an element.
- Values: `url()`, `slice`, `width`, `outset`, `repeat
```css
div {
  border: 10px solid transparent;
  border-image: url('border.png') 30 round;
}
```

### CSS margin properties

In CSS, margins are used to create space around elements, outside of any defined borders. You can customize the margins using various margin properties.

#### 🛠️ CSS Margin Properties

**1. `margin` (shorthand property)**

Sets the margin for all four sides of an element.
- Values: Sets all margins (top, right, bottom, left) in one line. Specific measurements (e.g., `10px`, `1em`), percentages
```css
/* One value: all sides */
div { margin: 20px; }

/* Two values: top-bottom | left-right */
div { margin: 10px 30px; }

/* Three values: top | left-right | bottom */
div { margin: 10px 20px 30px; }

/* Four values: top | right | bottom | left */
div { margin: 5px 10px 15px 20px; }
```

**2. `margin-top`**

Sets the top margin of an element.
```css
div {
  margin-top: 20px;
}
```

**3. `margin-right`**

Sets the right margin of an element.
```css
div {
  margin-right: 20px;
}
```

**4. `margin-bottom`**

Sets the bottom margin of an element.
```css
div {
  margin-bottom: 20px;
}
```

**5. `margin-left`**

Sets the left margin of an element.
```css
div {
  margin-left: 20px;
}
```

### CSS padding properties

In CSS, padding is the space between the content of an element and its border. You can customize the padding using various padding properties.

#### 🛠️ CSS Padding Properties

**1. `padding` (shorthand property)**

Sets the padding for all four sides of an element.
- Values: Sets all paddings (top, right, bottom, left) in one line. Specific measurements (e.g., `10px`, `1em`), percentages
```css
/* One value: all sides */
div { padding: 20px; }
/* Two values: top-bottom | left-right */
div { padding: 10px 30px; }
/* Three values: top | left-right | bottom */
div { padding: 10px 20px 30px; }
/* Four values: top | right | bottom | left */
div { padding: 5px 10px 15px 20px; }
```
**2. `padding-top`**

Sets the top padding of an element.
```css
div {
  padding-top: 20px;
}
```

**3. `padding-right`**

Sets the right padding of an element.
```css
div {
  padding-right: 20px;
}
```

**4. `padding-bottom`**

Sets the bottom padding of an element.
```css
div {
  padding-bottom: 20px;
}
```

**5. `padding-left`**

Sets the left padding of an element.
```css
div {
  padding-left: 20px;
}
```

#### Difference between margin and padding

- **Margin** is the space between the edge of an element and its surrounding content. It defines the distance between the element and its neighboring elements, such as other elements, borders, or other elements. In Margin property we can allow negative or float number values. We can set the margin property to auto margins.
- **Padding** is the space inside an element and is used to create space between the content and the border of an element. It defines the distance between the content and the border of an element. In Padding property we can allow only positive number values. We can set the padding property to auto padding.



### CSS text properties

In CSS, text properties are used to control the appearance and formatting of text within HTML elements. These properties allow you to customize font styles, sizes, colors, alignment, spacing, and more.

#### 🛠️ CSS Text Properties

**1. `color`**

Sets the color of the text.
```css
p {
  color: blue;
}
```

**2. `font-family`**

Specifies the font of the text.
```css
p {
  font-family: Arial, sans-serif;
}
```

**3. `font-size`**

Sets the size of the text.
```css
p {
  font-size: 16px;
}
```

**4. `font-weight`**

Sets the weight (boldness) of the text.
- Values: `normal` (default), `bold`, `bolder`, `lighter`, or numeric values (100 to 900).
```css
p {
  font-weight: bold;
}
```

**5. `font-style`**

Sets the style of the text.
- Values: `normal` (default), `italic`, `oblique`.
```css
p {
  font-style: italic;
}
```

**6. `text-align`**

Sets the horizontal alignment of the text.
- Values: `left` (default), `right`, `center`, `justify`.
```css
p {
  text-align: center;
}
```

**7. `text-decoration`**

Sets the decoration of the text.
- Values: `none` (default), `underline`, `overline`, `line-through`, `blink`.
```css
p {
  text-decoration: underline;
}
```

**8. `text-transform`**

Sets the capitalization of the text.
- Values: `none` (default), `capitalize`, `uppercase`, `lowercase`.
```css
p {
  text-transform: uppercase;
}
```

**9. `line-height`**

Sets the height of a line of text.
```css
p {
  line-height: 1.5;
}
```

**10. `letter-spacing`**

Sets the space between characters in the text.
```css
p {
  letter-spacing: 2px;
}
```

**11. `word-spacing`**

Sets the space between words in the text.
```css
p {
  word-spacing: 4px;
}
```

**12. `text-shadow`**

Adds shadow to the text.
```css
p {
  text-shadow: 2px 2px 5px gray;
}
```

**13. `white-space`**

Controls how whitespace inside an element is handled.
- Values: `normal` (default), `nowrap`, `pre`, `pre-wrap`, `pre-line`.
```css
p {
  white-space: nowrap;
}
```

**14. `text-indent`**

Sets the indentation of the first line of text.
```css
p {
  text-indent: 30px;
}
}
```


#### Difference between CSS border and outline

**CSS border** is used to draw a border around an element, while **CSS outline** is used to draw a line around an element. The outline is always drawn around the element, regardless of the element's size, while the border can be hidden or modified using CSS properties like `border-width` and `border-style`.


### CSS Link States

Links (`<a>`) in CSS have different states that let us style them depending on user interaction. These are called pseudo-classes for links.

**1. `a:link` → Normal, Unvisited Link**

Styles the link when it has not been visited.
```css
a:link {
  color: blue;
}
```

**2. `a:visited` → Visited Link**

Styles the link when it has been visited.
```css
a:visited {
  color: red;
}
```

**3. `a:hover` → Hovered Link**

Styles the link when the user hovers over it with the mouse.
```css
a:hover {
  color: green;
}
```

**4. `a:active` → Active Link**

Styles the link when it is being clicked or activated.
```css
a:active {
  color: yellow;
}
```

**5. `a:target` → Target Link**

Styles the link when it is the target of a link.
```css
a:target {
  color: orange;
}
```

**6. `a:lang` → Language-Specific Link**

Styles the link based on the language of the document.
```css
a:lang(fr) {
  color: purple;
}
```

**7. `a:focus` → Focused Link**

Styles the link when it is focused using the keyboard.
```css
a:focus {
  color: blue;
}
```



### Hide an HTML element in CSS

**1. `display: none` → Hidden Element**

- Completely removes the element from the page.
- The element does not take up space in the layout.
- It’s invisible and not accessible for screen readers.
```css
.hidden {
  display: none;
}
```

**2. `visibility: hidden` → Invisible Element**

- Keeps the element in the layout but hides it from view.
- The element still takes up space in the layout.
- It’s invisible and accessible for screen readers.
```css
.hidden {
  visibility: hidden;
}
```

**3. `opacity: 0` → Transparent Element**

- Makes the element partially transparent, but still visible.
- The element still takes up space in the layout.
- It’s invisible and accessible for screen readers.
```css
.hidden {
  opacity: 0;
}
```

> ✅ Use for **animations/fade** effects where you later set `opacity: 1`;.

**4. `pointer-events: none` → Invisible Element**

- Prevents the element from receiving mouse events (like clicks).
- The element still takes up space in the layout.
- It’s invisible and accessible for screen readers.
```css
.hidden {
  pointer-events: none;
}
```

**5. Move it Off-Screen**

- Use `position: absolute` to move the element outside the normal flow of the page.
- Set `left` and `top` properties to move it to the desired location.
```css
.hidden {
  position: absolute;
  left: -9999px;
  top: -9999px;
}
```

**6. `clip-path` or `clip` (Advanced)**

- Use `clip-path` or `clip` to create a custom shape for the element.
- Define a path or rectangle that defines the shape.
```css
.hidden {
  clip-path: polygon(0 0, 100% 0, 100% 100%, 0 100%);
}
```

**7. `height: 0; width: 0; overflow: hidden;`**

- Set the height and width of the element to 0.
- Set `overflow: hidden` to hide any content that overflows the element.
```css
.hidden {
  height: 0;
  width: 0;
  overflow: hidden;
}
```

#### 📊 Comparison Table

| Method | Takes Space? | Accessible? | Clickable? | Use Case |
|--------|--------------|-------------|------------|----------|
| `display: none` | ❌ No | ❌ No | ❌ No | Remove element completely |
| `visibility: hidden` | ✅ Yes | ❌ No | ❌ No | Keep layout spacing |
| `opacity: 0` | ✅ Yes | ✅ Yes | ✅ Yes | Animations, fades |
| Off-Screen (`left: -9999px`) | ❌ No | ✅ Yes | ❌ No | Screen readers only |
| `clip-path/clip` | ❌ No | ✅ Yes | ❌ No | Accessibility hiding |
| `height: 0; width: 0;` | ❌ No | ✅ Yes | ❌ No | Special cases |


#### Difference between `display: none` and `visibility: hidden`

- `display: none` hides the element completely, meaning it's removed from the layout and doesn't take up any space.
- `visibility: hidden` hides the element but keeps its layout and space, making it invisible but still accessible.


### Overlap elements in CSS

#### 🎯 Ways to Overlap Elements in CSS

**1. Using `position` + `z-index` (Most Common)**

use positioning (`absolute`, `relative`, `fixed`, `sticky`) and control stack order with `z-index`.

Example:
```html
<div class="box1"></div>
<div class="box2"></div>
```
```css
.box1 {
  position: relative;
  background: lightblue;
  width: 200px;
  height: 200px;
  z-index: 1; /* lower */
}

.box2 {
  position: absolute;
  top: 50px;
  left: 50px;
  background: tomato;
  width: 150px;
  height: 150px;
  z-index: 2; /* higher, overlaps */
}
```

**2. Using Negative Margins**

Elements can be pulled on top of others with negative margins.

Example:
```css
.box2 {
  margin-top: -100px; /* pulls it upward */
}
```

**3. Using CSS Grid or Flexbox (Layered Children)**

CSS Grid supports item layering with grid-area` or explicit stacking.

Example:
```css
.container {
  display: grid;
}

.item1 {
  grid-area: 1 / 1;
  background: lightgreen;
}

.item2 {
  grid-area: 1 / 1; /* same grid cell */
  background: orange;
  opacity: 0.8;
}
```

**4. Using Transform (`translate`, `rotate`, etc.)**

CSS `transform` can move elements without affecting the normal flow.

Example:
```css
.item3 {
  transform: translate(100px, 100px); /* moves 100px right and 100px down */
}
```

### CSS positioning

#### 🎯 CSS Positioning Properties

**1. `static` (Default)**

- The default position for all elements.
- Elements are placed in the normal document flow.
- `top`, `left`, `right`, `bottom`, and `z-index` do not apply.

Example:
```css
div {
  position: static;
}
```

**2. `relative`**

- Elements are positioned relative to their normal position.
- `top`, `left`, `right`, `bottom`, and `z-index` can be used.
- `z-index` controls the stacking order.
- Still takes up space in the layout.

Example:
```css
div {
  position: relative;
  top: 20px; /* moves 20px down from its normal spot */
  left: 10px;
}
```

**3. `absolute`**

- Positioned relative to the nearest ancestor with position: `relative` | `absolute` | `fixed` | `sticky`.
- Removed from normal document flow (other elements act like it doesn’t exist).
- Can overlap other elements.

Example:
```css
.parent {
  position: relative;
}

.child {
  position: absolute;
  top: 10px;
  left: 20px;
}
```


**4. `fixed`**

- Positioned relative to the viewport (browser window).
- Stays in the same position even when scrolling.
- Can overlap other elements.

Example:
```css
nav {
  position: fixed;
  top: 0;
  width: 100%;
}
```

**5. `sticky`**

- Acts like `relative` until a scroll threshold is reached, then it "sticks" like `fixed`.

Example:
```css
header {
  position: sticky;
  top: 0;
  background: white;
}
```

**6. `inherit` / `initial` / `unset`**

- `inherit`: Inherits the value from the parent element.
- `initial`: Resets the property to its default value.
- `unset`: Resets the property to its inherited value or its initial value, depending on the context.

Example:
```css
.parent {
  color: inherit;
}
```


### CSS overflow

- The `overflow` property controls how extra content (that doesn’t fit) is displayed.
- Applies to block containers with a fixed size (`height` / `width`).

`🔑 Syntax`
```css
overflow: hidden | scroll | auto | visible | initial | inherit;
```

**📌 Overflow Values**

**1. `visible` (default)**

- Content is not clipped.
- It overflows outside the container.

Example:
```css
.box {
  width: 200px;
  height: 100px;
  overflow: visible; /* default */
}
```

**2. `hidden`**

- Content is clipped (cut off).
- Extra content is not visible and no scrollbars appear.

Example:
```css
.box {
  width: 200px;
  height: 100px;
  overflow: hidden;
}
```

**3. `scroll`**

- Content is clipped.
- Scrollbars always appear (horizontal/vertical).

Example:
```css
.box {
  width: 200px;
  height: 100px;
  overflow: scroll;
}
```

**4. `auto`**

- Content is clipped.
- Scrollbars appear only if needed.

Example:
```css
.box {
  width: 200px;
  height: 100px;
  overflow: auto;
}
```

**5. `Overflow-x and Overflow-y`**

- `overflow-x` controls horizontal scrolling.
- `overflow-y` controls vertical scrolling.

Example:
```css
.box {
  width: 200px;
  height: 100px;
  overflow-x: scroll;
  overflow-y: auto;
}
```

### CSS float

The `float` property places an element on the left or right side of its container, allowing other content (like text) to flow around it.

**🔑 Syntax**

```css
selector {
  float: left | right | none | inline-start | inline-end;
}
```

#### 📌 Float Property Values

**1. `float: left;`**

- Moves the element to the left side of the container.
- Other content flows on the right.

Example:
```css
.box {
  width: 200px;
  height: 100px;
  background-color: lightblue;
  float: left;
}
```

**2. `float: right;`**

- Moves the element to the right side of the container.
- Other content flows on the left.

Example:
```css
.box {
  width: 200px;
  height: 100px;
  background-color: lightblue;
  float: right;
}
```

**3. `float: none;`**

- Removes the element from the normal flow and allows other content to flow around it.

Example:
```css
.box {
  width: 200px;
  height: 100px;
  background-color: lightblue;
  float: none;
}
```

**4. `float: inline-start;` / `float: inline-end;` (modern)**

- Floats element according to writing direction (LTR or RTL).
- Useful for internationalization.

Example:
```css
.box {
  width: 200px;
  height: 100px;
  background-color: lightblue;
  float: inline-start; /* or inline-end */
}
```

#### 🧹 Clearing Floats (clear Property)

To stop wrapping, use the `clear` property.

Example:
```css
.clearfix::after {
  content: "";
  display: table;
  clear: both;
}
```

- `clear: left` → stop floating left elements.
- `clear: right` → stop floating right elements.
- `clear: both` → stop floating elements on both sides.

### CSS `display` property

CSS `display` property controls how an element is rendered in the layout.

**1. `display: none`**

- Element is not rendered (completely removed from layout).
- Takes up no space.

> ✅ Used for modals, dropdowns, toggles.

Example:
```css
.hidden {
  display: none;
}
```

**2. `display: block`**

- Starts on a new line.
- Takes full width of its parent container.
- Supports `width`, `height`, `margin`, `padding`.

Example:
```css
.block {
  display: block;
  width: 100px;
  height: 100px;
  margin: 10px;
  padding: 10px;
}
```

> ✅ Examples: `<div>`, `<p>`, `<h1>`

**3. `display: inline`**

- Does not start on a new line.
- Takes width and height of content.
- Does not support `width`, `height`, `margin`, `padding`.

Example:
```css
.inline {
  display: inline;
  width: 100px;
  height: 100px;
  margin: 10px;
  padding: 10px;
}
```

> ✅ Examples: `<span>`, `<a>`, `<strong>`

**4. `display: inline-block`**

- Starts on a new line.
- Takes width and height of content.
- Does not support `width`, `height`, `margin`, `padding`.

Example:
```css
.inline-block {
  display: inline-block;
  width: 100px;
  height: 100px;
  margin: 10px;
  padding: 10px;
}
```

> ✅ Common for buttons, menus, badges.

**5. `display: flex`**

- Creates a flex container.
- Children (flex items) can align horizontally or vertically.
- Powerful for responsive layouts.

Example:
```css
.flex {
  display: flex;
  justify-content: center; /* Align items horizontally */
  align-items: center; /* Align items vertically */
}
```

> ✅ Use for navbar, grids, responsive UI.

**6. `display: inline-flex`**

- Combines `inline` and `flex` display types.
- Useful for creating inline flex items, like icons or buttons.

Example:
```css
.inline-flex {
  display: inline-flex;
  justify-content: center; /* Align items horizontally */
  align-items: center; /* Align items vertically */
}
```

> ✅ Useful when you want inline-flexible elements inside text.

**7. `display: grid`**

- Creates a grid container.
- Children (grid items) can be arranged in rows and columns.
- Perfect for creating complex layouts with rows and columns.

Example:
```css
.grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr); /* 3 equal-width columns */
  grid-template-rows: 100px 100px 100px; /* 3 equal-height rows */
  grid-gap: 10px; /* Add space between grid items */
}
```

> ✅ Perfect for page layouts, dashboards.

**8. `display: inline-grid`**

- Combines `inline` and `grid` display types.
- Useful for creating inline grid items, like icons or buttons.

Example:
```css
.inline-grid {
  display: inline-grid;
  justify-content: center; /* Align items horizontally */
  align-items: center; /* Align items vertically */
}
```

> ✅ Useful when you want inline-grid items inside text.

**9. `display: table`**

- Creates a table-like structure.
- Children (table cells) can be arranged in rows and columns.
- Perfect for creating complex layouts with rows and columns.

Example:
```css
.table {
  display: table;
  width: 100%; /* Make the table take up the full width */
  border-collapse: collapse; /* Collapse table borders */
}
```

✅ Children can use:

- `display: table-row`;
- `display: table-cell`;

> ✅ Perfect for creating complex layouts with rows and columns.

**10. `display: list-item`**

- Makes an element behave like a list item.
- Useful for creating bulleted lists, numbered lists, or any other list-style content.

Example:
```css
.list-item {
  display: list-item;
  list-style-type: disc; /* Use a disc icon as a list item */
}
```

✅ Useful for creating bulleted lists, numbered lists, or any other list-style content.


**11. `display: run-in` (⚠️ Deprecated in most browsers)**

- Makes an element behave like a run-in element.
- Useful for creating inline elements that behave like run-ins, such as inline lists or inline blocks.

Exaple:
```css
.run-in {
  display: run-in;
  font-size: 1.5em; /* Increase the font size */
}
```

✅ Useful for creating inline elements that behave like run-ins, such as inline lists or inline blocks.

**12. `display: contents`**

- Makes an element behave like its contents.
- Useful for creating elements that contain only their contents, without any additional markup.

Exaple:
```css
.contents {
  display: contents;
  font-weight: bold; /* Make the contents bold */
}
```

✅ Useful for creating elements that contain only their contents, without any additional markup.

**13. `display: flow-root`**

- Makes an element behave like a flow-root element.
- Useful for creating elements that behave like flow-root elements, such as flex containers or grid containers.

Exaple:
```css
.flow-root {
  display: flow-root;
  border: 1px solid #000; /* Add a border for visual clarity */
}
```

✅ Useful for creating elements that behave like flow-root elements, such as flex containers or grid containers.

#### 🎯 CSS Display Property:

| Display Value   | Description | Example Usage |
|-----------------|-------------|---------------|
| **none**        | Removes element completely from layout (not visible, no space taken). | `display: none;` (hide dropdown, modal, loader) |
| **block**       | Element starts on a new line and takes full width. | `<div>`, `<p>`, `<h1>` |
| **inline**      | Does not start on new line, only takes up as much width as content. Cannot set width/height. | `<span>`, `<a>` |
| **inline-block** | Behaves like inline but supports width, height, margin, padding. | Buttons, nav links, badges |
| **flex**        | Creates a flex container. Aligns children horizontally or vertically with flex properties. | Navbars, responsive layouts |
| **inline-flex** | Same as flex, but container behaves like inline element. | Inline flexible widgets |
| **grid**        | Creates a grid container. Children align in rows & columns. | Dashboards, web page layouts |
| **inline-grid** | Same as grid but container is inline. | Inline structured elements |
| **table**       | Behaves like `<table>`. | Custom tables, calendar layouts |
| **table-row**   | Behaves like `<tr>`. | Inside a table container |
| **table-cell**  | Behaves like `<td>`. | Table-like grid layouts |
| **list-item**   | Behaves like `<li>`. Adds list marker automatically. | Custom lists, menus |
| **contents**    | The element box disappears, but children remain in the flow. | Useful for accessibility wrappers |
| **flow-root**   | Creates a new block formatting context (BFC). Fixes float issues. | Containers wrapping floated elements |
| **run-in** ⚠️   | Deprecated. Behaves as block or inline depending on context. | Not recommended |



### 🎯 Ways to Vertically Center Text in CSS

**✅ 1. Using `line-height` (for single-line text)**

- Set the `line-height` equal to the container height.
- Works best when text is one line only.

Example:
```html
<div class="box">Centered Text</div>
```

```css
.box {
  height: 100px; /* Set the height of the box */
  line-height: 100px; /* Set line-height to match the box height */
  text-align: center; /* Center the text horizontally */
  background-color: lightblue; /* Optional: Add a background color */
  border: 1px solid #ccc; /* Optional: Add a border */
}
```

> 📌 Limitation: Does not work well for multi-line text.

**✅ 2. Using Flexbox (modern and best practice)**

- Set `display: flex` on the container.
- Use `align-items: center` (vertical) and `justify-content: center` (horizontal if needed).

Example:
```html
<div class="flex-box">
  <p>Vertically Centered with Flexbox</p>
</div>
```

```css
.flex-box {
  display: flex;
  align-items: center;      /* vertical */
  justify-content: center;  /* horizontal */
  height: 150px;
  border: 1px solid #ccc;
}
```

> 📌 Works well for multi-line text and more complex layouts.

**✅ 3. Using `position: absolute` (advanced)**

- Set `position: absolute` on the container.
- Use `top: 50%` and `transform: translateY(-50%)` to vertically center the content.

Example:
```html
<div class="absolute-box">
  <p>Vertically Centered with Absolute Positioning</p>
</div>
```

```css
.absolute-box {
  position: absolute;
  top: 50%;
  transform: translateY(-50%);
  height: 150px;
  border: 1px solid #ccc;
}
```

> 📌 Works well for complex layouts and when you need to center content relative to other elements.

**✅ 4. Using `position: fixed` (advanced)**

- Set `position: fixed` on the container.
- Use `top: 0` and `left: 0` to position the container at the top-left corner of the viewport.

Example:
```html
<div class="fixed-box">
  <p>Fixed Positioning</p>
</div>
```

```css
.fixed-box {
  position: fixed;
  top: 0;
  left: 0;
  height: 150px;
  border: 1px solid #ccc;
}
```

> 📌 Works well for fixed positioning and when you need to position elements relative to the viewport.

**✅ 5. Using `position: sticky` (advanced)**

- Set `position: sticky` on the container.
- Use `top: 0` to position the container at the top of the viewport.

Example:
```html
<div class="sticky-box">
  <p>Sticky Positioning</p>
</div>
```

```css
.sticky-box {
  position: sticky;
  top: 0;
  height: 150px;
  border: 1px solid #ccc;
}
```

> 📌 Works well for sticky positioning and when you need to position elements relative to the viewport.


**✅ 6. Using CSS Grid**

- Use `display: grid` on the container.
- Use `grid-template-columns` to define the number of columns.
- Use `grid-template-rows` to define the number of rows.

Example:
```html
<div class="grid-box">
  <p>Grid Layout</p>
</div>
```

```css
.grid-box {
  display: grid;
  place-items: center; /* shorthand for align + justify */
  height: 150px;
  border: 1px solid #ccc;
}
```

> ✅ Cleanest method if using grid layout.



### 🎯 Ways to Center an Image in CSS

**✅ 1. Center Horizontally (Block-Level Image)**

If the image is `display: block`, you can use `margin: auto`.

Example:
```html
<div class="container">
  <img src="image.jpg" alt="Centered Image">
</div>
```

```css
.container img {
  display: block;
  margin: 0 auto; /* centers horizontally */
  width: 200px;
}
```

**✅ 2. Center Horizontally (Text Align)**

If the image is inline (default), you can use `text-align: center` on the parent.

Example:
```html
<div class="container">
  <img src="image.jpg" alt="Centered Image">
</div>
```

```css
.container {
  text-align: center;
}
```

**✅ 3. Center Both Horizontally & Vertically (Flexbox)

Example:
```html
<div class="flex-container">
  <img src="image.jpg" alt="Centered Image">
</div>
```

```css
.flex-container {
  display: flex;
  justify-content: center; /* horizontal */
  align-items: center;     /* vertical */
  height: 300px;
  border: 1px solid #ccc;
}
```

**✅ 4. Center Both with CSS Grid**

Example:
```html
<div class="grid-container">
  <img src="image.jpg" alt="Centered Image">
</div>
```

```css
.grid-container {
  display: grid;
  place-items: center; /* shorthand for align + justify */
  height: 300px;
  border: 1px solid #ccc;
}
```

**✅ 5. Center with Absolute Positioning + Transform**

Example:
```html
<div class="relative-container">
  <img src="image.jpg" alt="Centered Image" class="center-img">
</div>
```

```css
.relative-container {
  position: relative;
  height: 300px;
  border: 1px solid #ccc;
}

.center-img {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
}
```


### 🎯 CSS Combinators

**✅ 1. Descendant Combinator (`space`)**

- Selects elements that are inside another element (no matter how deep).
- Written as: `A B`

Example:
```html
<div class="parent">
  <p>Child Paragraph</p>
  <span><p>Nested Paragraph</p></span>
</div>
```

```css
.parent p {
  color: red;
}
```

> ✅ Both `<p>` elements inside `.parent` turn red.


**✅ 2. Child Combinator (`>`)**

- Selects elements that are direct children only.
- Written as: `A > B`

Example:
```html
<div class="parent">
  <p>Direct Child</p>
  <span><p>Nested Child</p></span>
</div>
```

```css
.parent > p {
  color: blue;
}
```

> ✅ Only the first `<p>` (direct child of `.parent`) turns blue.


**✅ 3. Adjacent Sibling Combinator (`+`)**

- Selects an element that is immediately after another element.
- Written as: `A + B`

Example:
```html
<h2>Heading</h2>
<p>Paragraph 1</p>
<p>Paragraph 2</p>
```

```css
h2 + p {
  color: green;
}
```

> ✅ Only the first `<p>` after `<h2>` turns green.

**✅ 4. General Sibling Combinator (`~`)**

- Selects all siblings after a specified element.
- Written as: `A ~ B`

Example:
```html
<h2>Heading</h2>
<p>Paragraph 1</p>
<p>Paragraph 2</p>
```

```css
h2 ~ p {
  color: purple;
}
```

> ✅ Both `<p>` elements after `<h2>` turn purple.


### 🎯 pseudo-classes in CSS

- A pseudo-class defines a special state of an element.
- It doesn’t add anything to the HTML — it’s purely CSS-based.
- Example: Change a link’s color when hovered.
```css
a:hover {
  color: red;
}
```

#### 📌 Common Pseudo-Classes

**✅ 1. User Interaction States**

Used for links, buttons, inputs.

- `:hover` → when user hovers over element.
- `:active` → when element is being clicked.
- `:focus` → when input/element is focused.
- `:visited` → visited links.

Example:
```css
button:hover {
  background: blue;
}
button:active {
  background: navy;
}
input:focus {
  border-color: green;
}
a:visited {
  color: purple;
}
```


**✅ 2. Structural Pseudo-Classes**

Used for selecting elements by position.

- `:first-child` → first child of parent.
- `:last-child` → last child of parent.
- `:nth-child(n)` → selects nth child (pattern possible).
- `:nth-of-type(n)` → selects nth element of same type.
- `:only-child` → if element is only child of parent.

Example:
```css
ul li:first-child {
  font-weight: bold;
}
ul li:last-child {
  color: red;
}
ul li:nth-child(2) {
  color: blue;
}
p:only-child {
  background: lightyellow;
}
```

**✅ 3. Form States**

Special states of form elements.

- `:checked` → checkbox/radio checked.
- `:disabled` → disabled input.
- `:enabled` → enabled input.
- `:required` → required fields.
- `:optional` → optional fields.
- `:valid` / `:invalid` → input validation states.

Example:
```css
input:checked {
  outline: 2px solid green;
}
input:disabled {
  background: #eee;
}
input:invalid {
  border: 2px solid red;
}
```

**✅ 4. Negation**

- `:not(selector)` → selects elements that do not match.

**✅ 5. Dynamic UI**

- `:target` → element currently targeted by URL (#id).
- `:empty` → element with no children.

Example:
```css
#section:target {
  background: yellow;
}
div:empty {
  display: none;
}
```

### 🎯 pseudo-elements in CSS

- A pseudo-element lets you style specific parts of an element or generate content without modifying HTML.
- Written with two colons (`::`) (though older CSS allowed one `:`).
- Example: Insert content before or after an element.

Example:
```css
p::first-line {
  font-weight: bold;
}
```

#### 📌 Common Pseudo-Elements

**✅ 1. `::before`**

- Inserts content before an element’s content.

Example:
```css
<p class="quote">This is important.</p>
```

```css
.quote::before {
  content: "💡 ";
  color: orange;
}
```

**✅ 2. `::after`**

- Inserts content after an element’s content.

Example:
```html
<p class="required">Name</p>
```

```css
.required::after {
  content: " *";
  color: red;
}
```

**✅ 3. `::first-letter`**

- Styles the first letter of an element.

Example:
```css
p::first-letter {
  font-size: 2em;
  font-weight: bold;
  color: darkred;
}
```

**✅ 4. `::first-line`**

- Styles the first line of an element.

Example:
```css
p::first-line {
  font-style: italic;
  color: darkblue;
}
```

**✅ 5. `::selection`**

- Styles the selected text.

Example:
```css
::selection {
  background-color: #4472c4;
  color: white;
}
```

**✅ 6. `::placeholder`**

- Styles the placeholder text in an input field.

Example:
```css
input::placeholder {
  color: #999;
  font-style: italic;
}
```

**✅ 7. `::marker`**

- Styles the marker (bullet point) of a list item.

Example:
```css
ul li::marker {
  color: #ff0000;
  font-weight: bold;
}
```


### 🎯 CSS Gradient

- A gradient is a type of background image created with CSS.
- No image file needed → it’s generated by the browser.
- Defined using `linear-gradient()`, `radial-gradient()`, or `conic-gradient()`.

**🔑 Syntax**
```css
background: linear-gradient(direction, color1, color2, ...);
```

#### 📌 Types of Gradients in CSS

**✅ 1. Linear Gradient**

Colors blend in a straight line (top-to-bottom by default).

Example:
```css
.box {
  height: 150px;
  background: linear-gradient(to right, red, yellow);
}
```

**👉 Variations:**

- `to right` → left → right
- `to bottom` (default) → top → bottom
- Angle syntax: `45deg`, `180deg`

```css
background: linear-gradient(45deg, blue, pink);
```

**✅ 2. Radial Gradient**

Colors blend in a circular shape.

Example:
```css
.circle {
  width: 100px;
  height: 100px;
  background: radial-gradient(circle, red, yellow, green);
}
```

**👉 Shapes:**

- circle
- ellipse (default)

```css
background: radial-gradient(ellipse, blue, pink);
```

**✅ 3. Conic Gradient**

Colors rotate around a center point like a pie chart.

Example:
```css
.conic {
  width: 100px;
  height: 100px;
  background: conic-gradient(from 45deg, red, yellow, green);
}
```

> 👉 Can be used for charts, spinners, progress circles.

**🎨 Adding More Colors**

Example:
```css
.box {
  height: 150px;
  background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
}
```

> ✅ Creates a rainbow effect.

### 🎯 CSS 2D Transformation

- A way to modify the shape, size, and position of elements in 2D space.
- Applied with:
```css
transform: function(value);
```

- You can also combine multiple transformations:
```css
transform: translate(x, y) rotate(angle) scale(x, y) skew(x, y);
```

#### 📌 2D Transformation Functions

**✅ 1. `translate(x, y)`**

Moves an element from its original position.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: translate(50px, 50px);
}
```

- `x` and `y` are the horizontal and vertical offsets, respectively.

**✅ 2. `rotate(angle)`**

Rotates an element around its center point.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: rotate(45deg);
}
```

- `angle` is the rotation angle in degrees.
- `Positive angle` → clockwise
- `Negative angle` → counter-clockwise

**✅ 3. `scale(x, y)`**

Resizes element (zoom in/out).

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: scale(1.5, 1.5);
}
```

- `1.5` → increase size 150%
- `<1` → shrink (e.g., `0.5`)


**✅ 4. `skew(x-angle, y-angle)`**

Skews an element along the X and Y axes.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: skew(20deg, 30deg);
}
```

- `20deg` → skew along the X-axis
- `30deg` → skew along the Y-axis


**✅ 5. `matrix(a, b, c, d, e, f)`**

Combines all transformations in a single function. Rarely written by hand.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: matrix(1, 0.5, -0.5, 1, 30, 20);
}
```


### 🎯 CSS 3D Transformations

- CSS 3D transforms let you position and animate elements in three-dimensional space (X, Y, and Z axes).
- Unlike 2D, we can move forward/backward (Z-axis), creating depth.
- Controlled with `transform`, `transform-style`, and `perspective`.

#### 📌 Key 3D Transform Functions

**✅ 1. `translate3d(x, y, z)`**

Moves element along X (horizontal), Y (vertical), Z (depth).

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: translate3d(100px, 50px, 200px);
}
```

> - `translate3d(100px, 50px, 200px)` → Moves the element 100px to the right, 50px down, and 200px forward.

**✅ 2. `rotateX(angle)`**

Rotates element around the X-axis.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: rotateX(45deg);
}
```

> - `rotateX(45deg)` → Rotates the element 45 degrees around the X-axis.

**✅ 3. `rotateY(angle)`**

Rotates element around the Y-axis.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: rotateY(90deg);
}
```

> `rotateY(90deg)` → Rotates the element 90 degrees around the Y-axis.

**✅ 4. `rotateZ(angle)`**

Rotates element around the Z-axis.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: rotateZ(180deg);
}
```

> `rotateZ(180deg)` → Rotates the element 180 degrees around the Z-axis.

**✅ 5. `rotate3d(x, y, z, angle)`**

Rotates element around a custom axis defined by the given vector.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: rotate3d(1, 1, 1, 45deg);
}
```

> `rotate3d(1, 1, 1, 45deg)` → Rotates the element 45 degrees around a custom axis defined by the vector (1, 1, 1).

**✅ 6. `scale3d(x, y, z)`**

Scales element along the X, Y, and Z axes.

Example:
```css
.box {
  width: 100px;
  height: 100px;
  background: red;
  transform: scale3d(2, 2, 2);
}
```

**🎨 Perspective in 3D**

To make 3D transformations look real, use `perspective`.
It defines how far the viewer is from the object.

Example:
```css
body {
  perspective: 800px;
}
```

- Smaller value (`200px`) → strong depth (dramatic tilt)
- Larger value (`2000px`) → subtle depth


### CSS Animations

CSS gives two main, complementary ways to animate things:

- **Transitions** — animate between two states (good for hover / toggle).
- **Animations (`@keyframes`)** — create explicit multi-step sequences, loops, complex timing.


**1) `Transition` (simple state-based animation)**

Use transition to animate when a property changes (e.g., on `:hover`, or when a class is toggled).

Example:
```html
<button class="btn">Hover me</button>

<style>
.btn {
  background: #2575fc;
  color: #fff;
  padding: 12px 22px;
  border-radius: 6px;
  border: none;
  cursor: pointer;

  /* animate transform and background-color when they change */
  transition: transform 250ms ease, background-color 250ms ease;
}

.btn:hover {
  transform: translateY(-4px) scale(1.02);
  background-color: #1a5ad1;
}
</style>
```


**2) Keyframe animations (`@keyframes`) — full control**

Define named sequences with `@keyframes`, then assign them via animation properties.

Example:
```html
<div class="spinner"></div>

<style>
.spinner{
  width: 64px;
  height: 64px;
  border-radius: 50%;
  background: conic-gradient(#4facfe,#00f2fe);
  animation: spin 1.2s linear infinite;
}

/* keyframes define the animation steps */
@keyframes spin {
  from { transform: rotate(0deg); }
  to   { transform: rotate(360deg); }
}
</style>
```


**3) Animation properties (longhand + shorthand)**

Longhand properties:

- `animation-name` — the `@keyframes` identifier.
- `animation-duration` — how long one cycle lasts (`s` or `ms`).
- `animation-timing-function` — easing (`linear`, `ease`, `ease-in`, `cubic-bezier(...)`, `steps(n)`).
- `animation-delay` — wait before starting (can be negative to start mid-animation).
- `animation-iteration-count` — `1`, `infinite`, or a number.
- `animation-direction` — `normal`, `reverse`, `alternate`, `alternate-reverse`.
- `animation-fill-mode` — `none`, `forwards`, `backwards`, `both` (controls what happens before/after animation).
- `animation-play-state` — `running` or `paused`.
- `animation` — shorthand: `animation: name duration timing-function delay iteration-count direction fill-mode play-state;`

Example (shorthand):
```css
.box {
  animation: enter 600ms cubic-bezier(.2,.8,.2,1) 0s 1 normal forwards;
}
```

**4) Keyframes syntax**

`@keyframes name { 0% { ... } 50% { ... } 100% { ... } }`
You can use `from`/`to` instead of `0%`/`100%`. Use percentages to control intermediate steps.

Example:
```css
@keyframes pulse {
  0%   { transform: scale(1); opacity: 1; }
  50%  { transform: scale(1.08); opacity: 0.9; }
  100% { transform: scale(1); opacity: 1; }
}
```

**5) Timing functions / easing**

- Keywords: `linear`, `ease`, `ease-in`, `ease-out`, ease-in-out.
- cubic-bezier(x1,y1,x2,y2): precise control. Example: `cubic-bezier(.25,.1,.25,1)` (very common).
- steps(n, start|end): for discrete jumps — great for sprite animations.

  - `steps(10, end)` steps through 10 frames.

Example: sprite animation with steps
```css
.sprite {
  width: 100px; height: 100px;
  background: url('sprite.png') 0 0 no-repeat;
  animation: play 1s steps(10) infinite;
}
@keyframes play { to { background-position: -1000px 0; } } /* 10 frames * 100px */
```

**6) Useful patterns & examples**

A — Entrance animation that stays at final state

Example:
```css
.fade-in {
  animation: fadeIn 500ms ease forwards;
}
@keyframes fadeIn {
  from { opacity: 0; transform: translateY(12px); }
  to   { opacity: 1; transform: translateY(0); }
}
/* `forwards` makes the final state persistent */
```

B — Flip card (3D, needs `preserve-3d`)

Example:
```html
<div class="scene">
  <div class="card">
    <div class="front">Front</div>
    <div class="back">Back</div>
  </div>
</div>

<style>
.scene { perspective: 1000px; width:200px; height:200px; }
.card {
  width:100%;height:100%; position:relative;
  transform-style: preserve-3d;
  transition: transform 700ms;
}
.scene:hover .card { transform: rotateY(180deg); }
.card > div { position:absolute; inset:0; backface-visibility:hidden; display:flex; align-items:center; justify-content:center; }
.card .back { transform: rotateY(180deg); }
</style>
```

C — Staggered list using CSS variable delay

Example:
```html
<ul class="list">
  <li style="--i:0">Item 1</li>
  <li style="--i:1">Item 2</li>
  <li style="--i:2">Item 3</li>
</ul>

<style>
.list li {
  opacity: 0;
  transform: translateY(12px);
  animation: slideIn 360ms cubic-bezier(.2,.8,.2,1) forwards;
  animation-delay: calc(var(--i) * 100ms);
}
@keyframes slideIn { to { opacity:1; transform:translateY(0);} }
</style>
```

D — Pause/resume with CSS and JS

Example:
```javascript
const el = document.querySelector('.spinner');
el.style.animationPlayState = 'paused'; // pause
el.style.animationPlayState = 'running'; // resume
```

**7) Transitions vs Animations vs Transform**

- **Transitions**: animate between two states automatically; simpler.
- **Animations**: multi-step, can loop, more control.
- **Transform**: property you should prefer to animate (`transform: translate/scale/rotate`) because they use compositing and don’t trigger layout.

Best properties to animate for performance:
`transform` and `opacity` (they are handled on the compositor thread).

Avoid animating (if possible): `width`, `height`, `top`, `left`, `margin`, `padding`, `left/right` — those trigger layout/reflow and are expensive.


**8) Performance tips**

- Prefer `transform` + `opacity`.
- Use `will-change` sparingly to hint the browser:

```css
.animating { will-change: transform, opacity; }
```

But don’t leave `will-change` permanently — it can consume memory.

Promote to GPU if necessary: `transform: translateZ(0);` — but use only when needed.

- Use `requestAnimationFrame` in JS if you must update styles every frame.
- Use `prefers-reduced-motion` to respect user preference.


**9) Accessibility — prefers-reduced-motion**

Respect users who prefer reduced motion:
```css
@media (prefers-reduced-motion: reduce) {
  * { animation-duration: 0.001ms !important; transition-duration: 0.001ms !important; }
}
```

Better to *turn off* nonessential motion, reduce durations, or use simple fades.



**10) Chaining, sequencing, negative delays, multiple animations**

- Multiple animations on same element: comma-separated lists for `animation-name`, `animation-duration`, etc.
- Negative delay: `animation-delay: -0.5s`; starts the animation already part-way through.
- Sequence: either use `animation-delay` to stagger or listen to `animationed` in JS to start the next animation.

Example multiple animations:
```css
.box {
  animation: wiggle 1s ease infinite, colorShift 3s linear infinite;
}
```


**11) Events & JS control**

Important DOM events:

- `animationstart` — when animation begins.
- `animationiteration` — on each loop iteration.
- `animationend` — when the animation finishes.

Example;
```js
el.addEventListener('animationend', () => {
  console.log('done');
});
```

also set `element.style.animation = 'name 1s ease'` to start programmatically.



### CSS box-sizing property

The `box-sizing` property defines how the browser calculates the total width and height of an element.
It determines whether padding and border are included in the element’s size or added on top of it.

#### 📌 Available Values

**✅ 1. `content-box` (default)**

- The width/height applies only to the content box.
- Padding and border are added outside, increasing the final element size.

Example:
```css
.box {
  width: 200px;
  padding: 20px;
  border: 10px solid black;
  box-sizing: content-box;
}
```

📏 Calculation:

- Content: `200px`
- Padding: `20px + 20px = 40px`
- Border: `10px + 10px = 20px`
- Total width = 200 + 40 + 20 = 260px


**✅ 2. `border-box` (commonly used)**

- The width/height includes content + padding + border.
- The content area shrinks to fit inside.

Example:
```css
.box {
  width: 200px;
  padding: 20px;
  border: 10px solid black;
  box-sizing: border-box;
}
```

📏 Calculation:

- Total box = `200px` (fixed)
- Padding + border are inside that width.
- Content width = `200 - 40 - 20 = 140px`.

**✅ 3. inherit**

- Inherits the `box-sizing` value from the parent element.



### Make website responsive using CSS

Responsive design means website automatically adjusts to different screen sizes, orientations, and resolutions — providing the best user experience on all devices.

#### 📌 Key Techniques to Make a Website Responsive

**✅ 1. Use Fluid Layouts with Relative Units**

Instead of fixed pixel values (`px`), use percentages, `em`, or `rem`.

Example:
```css
.container {
  width: 100%;
  max-width: 1200px;
  margin: 0 auto;
}
```

> 👉 The container scales with the screen.


**✅ 2. Apply Viewport Meta Tag**

Required in HTML `<head>` so browsers scale correctly.

Example:
```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

> 👉 This tells the browser to scale the page to the device's width and sets the initial zoom level to 1.0.

**✅ 3. Use Media Queries**

Use CSS media queries to apply different styles based on screen size.

Example:
```css
/* Small devices (phones) */
@media (max-width: 600px) {
  body {
    font-size: 14px;
  }
  .grid {
    grid-template-columns: 1fr;
  }
}

/* Medium devices (tablets) */
@media (min-width: 601px) and (max-width: 1024px) {
  .grid {
    grid-template-columns: 1fr 1fr;
  }
}

/* Large devices (desktops) */
@media (min-width: 1025px) {
  .grid {
    grid-template-columns: 1fr 1fr 1fr;
  }
}
```

> 👉 This ensures that the layout adapts to different screen sizes, providing a better user experience.

**✅ 4. Use Flexbox & Grid**

Modern layout systems make responsiveness easy.

Example:
```css
.container {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
}
.item {
  flex: 1 1 300px; /* Grow, shrink, min-width */
}
```

> 👉 This allows you to create flexible layouts that adapt to different screen sizes.

**✅ 5. Make Images Responsive**

Prevent images from breaking layouts.

Example:
```css
img {
  max-width: 100%;
  height: auto;
}
```

> 👉 Image scales down but doesn’t overflow.


**✅ 6. Use Responsive Typography**

Instead of fixed `px`, use `em`, `rem`, or `clamp()`.

Example:
```css
h1 {
  font-size: clamp(1.5rem, 5vw, 3rem);
}
```

> 👉 Scales between `1.5rem` (mobile) and `3rem` (desktop).

**✅ 7. Use CSS Frameworks (Optional)**

Frameworks like Bootstrap, Tailwind CSS, Material UI provide ready-made responsive classes.

Example in Tailwind CSS:
```html
<div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-4">
  <div class="p-4 bg-blue-300">Item 1</div>
  <div class="p-4 bg-blue-400">Item 2</div>
  <div class="p-4 bg-blue-500">Item 3</div>
</div>
```

#### 🛠️ Real-World Example (Responsive Card Layout)

```html
<div class="grid">
  <div class="card">Card 1</div>
  <div class="card">Card 2</div>
  <div class="card">Card 3</div>
</div>
```

```css
.grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 20px;
}

/* Tablet */
@media (min-width: 600px) {
  .grid {
    grid-template-columns: 1fr 1fr;
  }
}

/* Desktop */
@media (min-width: 1024px) {
  .grid {
    grid-template-columns: 1fr 1fr 1fr;
  }
}

.card {
  background: #4facfe;
  padding: 20px;
  color: white;
  text-align: center;
  font-size: 20px;
  border-radius: 10px;
}
```

### CSS flexbox

**Flexbox (Flexible Box Layout)** is a 1D layout system in CSS that makes it easy to arrange elements in rows or columns with automatic alignment, spacing, and resizing.

👉 Unlike older layout methods (`float`, `inline-block`, `table`), Flexbox is responsive, dynamic, and easy to control.


**📌 The Two Parts of Flexbox**

1. **Flex Container** → the parent element with `display: flex;`.
2. **Flex Items** → the children inside the container.

#### ✅ Flex Container Properties

**1. `display: flex;`**

Enables flexbox on a container.

Example:
```css
.container {
  display: flex;
}
```

**2. `flex-direction;`**

Defines the main axis (direction of items).

Example:
```css
.container {
  display: flex;
  flex-direction: row;       /* default → left to right */
  flex-direction: row-reverse;
  flex-direction: column;    /* top to bottom */
  flex-direction: column-reverse;
  flex-direction: row wrap;  /* items wrap to the next line */
  flex-direction: row wrap reverse;
  flex-direction: column wrap; /* items wrap to the next column */
  flex-direction: column wrap reverse;
}
```

**3. `justify-content;`**

Controls how items are aligned along the main axis (left/right/center).

Example:
```css
.container {
  display: flex;
  justify-content: center;    /* default → left */
  justify-content: flex-end;  /* right */
  justify-content: flex-start; /* left */
  justify-content: space-between; /* evenly distributed */
  justify-content: space-around; /* evenly distributed with equal space around */
  justify-content: space-evenly; /* evenly distributed with equal space around */
}
```

**4. `align-items;`**

Controls how items are aligned along the cross axis (top/bottom/center).

Example:
```css
.container {
  display: flex;
  align-items: center;        /* default → top */
  align-items: flex-end;      /* bottom */
  align-items: flex-start;    /* top */
  align-items: stretch;       /* stretch to fill the container */
  align-items: baseline;      /* align items at their baselines */
  align-items: self-start;    /* align items at their start */
  align-items: self-end;      /* align items at their end */
  align-items: self-center;   /* align items at their center */
  align-items: self-baseline; /* align items at their baselines */
  align-items: self-stretch;  /* stretch items to fill the container */
}
```

**5. `flex-wrap;`**

Controls whether items should wrap onto multiple lines.

Example:
```css
.container {
  display: flex;
  flex-wrap: nowrap;         /* default → wrap */
  flex-wrap: wrap;           /* wrap */
  flex-wrap: wrap-reverse;   /* reverse wrap */
}
```

**6. `align-content;`**

Controls how items are aligned along the cross axis when there is not enough space to fill the entire cross axis.

Example:
```css
.container {
  display: flex;
  align-content: flex-start; /* default → center */
  align-content: flex-end;   /* bottom */
  align-content: center;     /* center */
  align-content: space-between; /* evenly distributed */
  align-content: space-around; /* evenly distributed with equal space around */
  align-content: space-evenly; /* evenly distributed with equal space around */
  align-content: stretch;     /* stretch items to fill the container */
  align-content: baseline;    /* align items at their baselines */
}
```

**✅ Flex Item Properties**

**1. `order`**

Controls item order (default = 0).

Example:
```css
.item {
  order: 2; /* default → 0 */
}
```

**2. `flex-grow`**

Controls how much an item should grow relative to other items (default = 0).

Example:
```css
.item {
  flex-grow: 2; /* default → 0 */
}
```

**3. `flex-shrink`**

Controls how much an item should shrink relative to other items (default = 1).

Example:
```css
.item {
  flex-shrink: 2; /* default → 1 */
}
```

**4. `flex-basis`**

Controls the initial size of an item (default = auto).

Example:
```css
.item {
  flex-basis: 100px; /* default → auto */
}
```

**5. `flex` (Shorthand)**

Combines `flex-grow`, `flex-shrink`, and `flex-basis` into one property (default = 0 1 auto).

Example:
```css
.item {
  flex: 2 2 100px; /* default → 0 1 auto */
}
```

### CSS Grid

**CSS Grid Layout** is a two-dimensional layout system in CSS.
Unlike Flexbox (1D: row OR column), Grid can handle both rows and columns at the same time, making it perfect for web page layouts, dashboards, galleries, etc.

**📌 The Two Parts of CSS Grid**

1. **Grid Container** → Parent element with `display: grid`;.
2. **Grid Items** → Child elements inside the container.


#### ✅ Grid Container Properties

**1. `display: grid;`**

Enables grid layout on the container.

Example:
```css
.container {
  display: grid;
}
```

**2. `grid-template-columns` & `grid-template-rows`**

Define the number of columns and rows in the grid, and their sizes.

Example:
```css
.container {
  display: grid;
  grid-template-columns: 200px 200px 200px; /* 3 fixed columns */
  grid-template-rows: 100px 150px;          /* 2 rows */
}
```

👉 Can use `px`, `%`, `fr` (fractional unit), `auto`.

Example with `fr`:
```css
grid-template-columns: 1fr 2fr 1fr; /* middle column is double size */
```

**3. `gap` (or `row-gap`, `column-gap`)**

Adds space between grid items and between rows/columns.

Example:
```css
.container {
  display: grid;
  grid-template-columns: 200px 200px 200px;
  grid-template-rows: 100px 150px;
  gap: 10px; /* space between grid items */
}
```


**4. `justify-items;` (horizontal alignment of items)**

Example:
```css
.container {
  justify-items: start;  /* left */
  justify-items: end;    /* right */
  justify-items: center;
  justify-items: stretch; /* default */
  justify-items: baseline; /* vertical alignment of items */
  justify-items: space-between; /* space between items */
  justify-items: space-around; /* space between items */
  justify-items: space-evenly; /* space between items */
}
```

**5. `align-items;` (vertical alignment of items)**

Example:
```css
.container {
  align-items: start;  /* top */
  align-items: end;    /* bottom */
  align-items: center;
  align-items: stretch; /* default */
  align-items: baseline; /* vertical alignment of items */
  align-items: space-between; /* space between items */
  align-items: space-around; /* space between items */
  align-items: space-evenly; /* space between items */
}
```

**6. `justify-content;` (horizontal alignment of items)**

Example:
```css
.container {
  justify-content: start;  /* left */
  justify-content: end;    /* right */
  justify-content: center;
  justify-content: space-between; /* space between items */
  justify-content: space-around; /* space between items */
  justify-content: space-evenly; /* space between items */
}
```

**7. `align-content;` (vertical alignment of items)**

Example:
```css
.container {
  align-content: start;  /* top */
  align-content: end;    /* bottom */
  align-content: center;
  align-content: stretch; /* default */
  align-content: baseline; /* vertical alignment of items */
  align-content: space-between; /* space between items */
  align-content: space-around; /* space between items */
  align-content: space-evenly; /* space between items */
}
```

**8. `grid-template-areas;`**

Create named regions for layouts.

Example:
```css
.container {
  display: grid;
  grid-template-areas:
    "header header"
    "sidebar main"
    "footer footer";
  grid-template-columns: 200px 1fr;
  grid-template-rows: auto 1fr auto;
}
.header  { grid-area: header; }
.sidebar { grid-area: sidebar; }
.main    { grid-area: main; }
.footer  { grid-area: footer; }
```

#### ✅ Grid Item Properties

**1. `grid-column` & `grid-row`**

Control where an item starts and ends.

Example:
```css
.item {
  grid-column: 1 / 3; /* start at column 1, end at column 3 */
  grid-row: 2 / 4;    /* start at row 2, end at row 4 */
}
```

**2. `grid-column-start` & `grid-column-end`**

Control where an item starts and ends.

Example:
```css
.item {
  grid-column-start: 1; /* start at column 1 */
  grid-column-end: 3;   /* end at column 3 */
}
```

**3. `grid-row-start` & `grid-row-end`**

Control where an item starts and ends.

Example:
```css
.item {
  grid-row-start: 2; /* start at row 2 */
  grid-row-end: 4;   /* end at row 4 */
}
```

**4. `grid-column-gap` & `grid-row-gap`**

Control the spacing between columns and rows.

Example:
```css
.grid-container {
  grid-column-gap: 20px; /* set the gap between columns */
  grid-row-gap: 10px;    /* set the gap between rows */
}
```

**5. `justify-self` & `align-self`**

Control how an item is aligned within its grid cell.

Example:
```css
.item {
  justify-self: center; /* center the item horizontally within its grid cell */
  align-self: stretch;  /* stretch the item to fill its grid cell */
}
```

**6. `grid-auto-flow`**

Control how new items are placed in the grid.

Example:
```css
.grid-container {
  grid-auto-flow: row; /* place new items in the grid row by row */
  grid-auto-flow: column; /* place new items in the grid column by column */
}
```

**7. `grid-auto-columns` & `grid-auto-rows`**

Control the size of new grid items.

Example:
```css
.grid-container {
  grid-auto-columns: 100px; /* set the size of new items to 100px */
  grid-auto-rows: 100px;    /* set the size of new items to 100px */
}
```

**8. `grid-template-areas`**

Define areas in the grid and assign them to elements.

Example:
```css
.grid-container {
  grid-template-areas: "header header"
                       "sidebar main"
                       "footer footer";
}
```

**9. `grid-area`**

Define the area for an element in the grid.

Example:
```css
.item3 {
  grid-area: 2 / 1 / 3 / 3; /* row-start / col-start / row-end / col-end */
}
```

#### 🛠️ Real-World Example: Responsive Page Layout
```html
<div class="container">
  <header class="header">Header</header>
  <nav class="sidebar">Sidebar</nav>
  <main class="main">Main Content</main>
  <footer class="footer">Footer</footer>
</div>
```

```css
.container {
  display: grid;
  grid-template-areas:
    "header header"
    "sidebar main"
    "footer footer";
  grid-template-columns: 200px 1fr;
  grid-template-rows: auto 1fr auto;
  gap: 20px;
  height: 100vh;
}
.header  { grid-area: header; background: #4facfe; }
.sidebar { grid-area: sidebar; background: #ff6f61; }
.main    { grid-area: main; background: #43e97b; }
.footer  { grid-area: footer; background: #f093fb; }
```

> ✅ Layout adapts to desktop/tablet/mobile easily.

**🌀 Responsive Example with `auto-fit` and `minmax()`**

```css
.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}
.card {
  background: #4facfe;
  color: white;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
}
```

> ✅ Automatically adjusts number of columns depending on screen size.


#### 📊 Difference Between **Flexbox** and **Grid**

| Feature              | **Flexbox** 🧩 | **Grid** 🗂️ |
|----------------------|----------------|--------------|
| **Layout Type**      | **1D (one-dimensional)** → either **row OR column** | **2D (two-dimensional)** → handles **rows AND columns** |
| **Best For**         | Smaller components (navbars, buttons, cards, toolbars) | Full page layouts, complex grids, dashboards, galleries |
| **Main Axis Control** | Yes → `justify-content` controls row/column alignment | Yes + cross-axis control with **grid lines** |
| **Cross Axis Control** | Limited → `align-items` / `align-content` | Very strong → control exact row & column placement |
| **Item Placement**   | Automatic order (can use `order`) | Place anywhere with `grid-column`, `grid-row`, or `grid-area` |
| **Content vs Layout** | Content-first → items push and wrap automatically | Layout-first → define structure (rows/cols) first, then place items |
| **Responsiveness**   | Great with `flex-wrap` and `gap` | Great with `auto-fit`, `auto-fill`, `minmax()` |
| **Learning Curve**   | Easier for beginners | More powerful but slightly more complex |
| **Browser Support**  | Very strong (all modern browsers) | Strong (all modern browsers, but flexbox came earlier) |


### `@keyframes`

The `@keyframes` at-rule defines the steps of an animation sequence in CSS.
It lets you specify how an element should look at different points during an animation (e.g., at 0%, 50%, 100%).
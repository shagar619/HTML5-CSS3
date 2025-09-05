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

Output:
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
Output:
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

Output:
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
Output:
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

Output:
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


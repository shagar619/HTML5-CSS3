<!-- markdownlint-disable MD012 MD026 MD001 MD022 MD032 MD029 MD019 MD034 MD031 MD047 MD040 MD009 MD058 MD024 MD033 MD041 MD045 MD007 MD036  -->

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

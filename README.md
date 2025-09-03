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


### HTML Tag

A tag is the building block of HTML.

- Tags are keywords wrapped in angle brackets (`<>`).
- Most tags come in pairs: opening tag `<tagname>` and closing tag `</tagname>`.
- Some tags are self-closing (e.g., `<img />`, `<br />`, `<input />`).

✅ Example:
```html
<p>This is a paragraph.</p>
```
Here:
- `<p>` = opening tag
- `</p>` = closing tag

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
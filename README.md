<!-- markdownlint-disable MD012 MD026 MD001 MD022 MD032 MD029 MD019 MD034 MD031 MD047 MD040 MD009 MD058 MD024 MD033 MD041 MD045 MD007  -->

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
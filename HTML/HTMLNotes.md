# 🌐 HTML Notes (Super Easy for Beginners)

## 📌 What is HTML?

HTML stands for **HyperText Markup Language**.

Let’s understand it in a very simple way:

* **HyperText** → Text + Images + Videos + Links
* **Markup** → Structure (using tags)
* **Language** → Used to create websites

👉 So, HTML is used to **build the structure of a website**.

---

## 🧱 Basic Structure of HTML (Boilerplate Code)

This is the basic code every HTML page needs:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Website</title>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```

### 🔍 What does each tag do?

* `<!DOCTYPE html>` → Tells browser we are using **HTML5**
* `<html>` → Main root of the website
* `<head>` → Contains important info (title, meta, CSS)
* `<title>` → Name shown on browser tab
* `<body>` → Visible content of website

---

## 🔠 Headings in HTML

There are **6 types of headings**:

```html
<h1>Biggest Heading</h1>
<h2>...</h2>
<h3>...</h3>
<h4>...</h4>
<h5>...</h5>
<h6>Smallest Heading</h6>
```

👉 Use `<h1>` for main title and others for smaller titles.

---

## 📄 Paragraph Tag

Used to write text:

```html
<p>This is a paragraph</p>
```

---

## 🏷️ What are Tags?

Tags are used to **create structure** in HTML.

Example:

```html
<p>Hello</p>
```

### Types of Tags

### 1️⃣ Container Tags

* Have opening **and** closing tags
* Example:

```html
<p>Hello</p>
<h1>Title</h1>
```

### 2️⃣ Empty Tags

* Only opening tag
* No closing tag needed

Examples:

```html
<br>   <!-- Line break -->
<hr>   <!-- Horizontal line -->
```

---

## 🔗 Anchor Tag (Links)

Used to add links:

```html
<a href="https://google.com">Go to Google</a>
```

👉 Open link in new tab:

```html
<a href="https://google.com" target="_blank">Open Google</a>
```

---

## 🧠 Semantic Tags (Better Structure)

These make your website **clean and easy to understand**.

```html
<header>Top part</header>
<nav>Menu / Navbar</nav>
<section>Content section</section>
<article>Text content</article>
<footer>Bottom part</footer>
```

👉 They help developers and search engines understand your website.

---

## 📋 Lists in HTML

Lists are used to show items.

### 🔹 1. Unordered List (Bullets)

```html
<ul>
  <li>Sugar</li>
  <li>Rice</li>
  <li>Tea</li>
</ul>
```

### 🔹 2. Ordered List (Numbers/Letters)

```html
<ol>
  <li>Sugar</li>
  <li>Rice</li>
  <li>Tea</li>
</ol>
```

👉 Output:

1. Sugar
2. Rice
3. Tea

---

## 🧾 List Item Tag

Used inside lists:

```html
<li>Item Name</li>
```


---
## 🧾 Tables
Tables are the combination of rows and columns.

1. <table>...</table>
2. <tr>....</tr> (Table Row)
3. <th>...</th> (Table Header)
4. <td>...</td> (Table Data)
5. <thead>...</thead>
6. <tbody>...</tbody>
7. <tfoot>...</tfoot>
8. <caption>...</caption> (Title or description of table)

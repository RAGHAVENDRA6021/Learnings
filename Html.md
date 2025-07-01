
# 📘 HTML Basics

**HTML** (HyperText Markup Language) is used to structure content on the web using elements and tags.

---

## 🔠 Heading Tags

HTML provides six levels of headings:

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
````

---

## 📋 List Tags

### ✅ Ordered List (`<ol>`)

Displays items in a numbered sequence.

```html
<ol>
  <li>First item</li>
  <li>Second item</li>
</ol>
```

### 🔘 Unordered List (`<ul>`)

Displays items in a bulleted format.

```html
<ul>
  <li>Item A</li>
  <li>Item B</li>
</ul>
```

---

## 🖼️ Image Tag (`<img>`)

Used to display images. It is a **self-closing tag**.

```html
<img src="image.jpg" alt="Description" />
```

---

## ↔️ Inline vs Block Elements

### 🧱 Block Elements

* Start on a **new line**
* Occupy full width

Example:

```html
<div>This is a block element</div>
```

### 🧩 Inline Elements

* Stay on the **same line**
* Occupy only the necessary width

Example:

```html
<span>This is an inline element</span>
```

---

## 🌀 `<marquee>` Tag (Deprecated)

Scrolls text across the screen:

```html
<marquee>This is scrolling text</marquee>
```

> ⚠️ **Deprecated:** Avoid using this in modern HTML.

---

## 📝 Input Tag (`<input>`)

Used in forms to capture user input.

### 🔘 Radio Buttons

```html
<input type="radio" name="gender" value="male" /> Male
<input type="radio" name="gender" value="female" /> Female
```

### ☑️ Checkboxes

```html
<input type="checkbox" name="vehicle" value="Bike" /> Bike
<input type="checkbox" name="vehicle" value="Car" /> Car
```

---

## 🔽 Select Tag (`<select>`)

Creates a dropdown menu:

```html
<select name="fruits">
  <option value="apple">Apple</option>
  <option value="banana">Banana</option>
  <option value="orange">Orange</option>
</select>
```

---

## 📊 Table Tag

Used to present tabular data:

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
    <th>City</th>
  </tr>
  <tr>
    <td>John</td>
    <td>25</td>
    <td>Delhi</td>
  </tr>
  <tr>
    <td>Ravi</td>
    <td>30</td>
    <td>Mumbai</td>
  </tr>
</table>
```

**Key Tags:**

* `<table>`: Main table container
* `<tr>`: Table row
* `<th>`: Header cell (bold & centered)
* `<td>`: Data cell

---

## 🧠 Semantic HTML & DOM Notes

* **Semantic HTML** uses meaningful tags (like `<article>`, `<section>`, `<nav>`) for better accessibility and SEO.
* **DOM (Document Object Model)** represents HTML as a tree of nodes.

### Attributes:

* `id`: Uniquely identifies a single element.
* `class`: Groups multiple elements with similar styles or behavior.

### Forms:

To link a label with an input:

```html
<label for="email">Email:</label>
<input type="email" id="email" name="email" />
```

📌 `for` in `<label>` must match the `id` of the `<input>`.



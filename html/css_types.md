
---

### 🌐 1. **Inline CSS**
CSS is written directly in the `style` attribute of an HTML tag.

```html
<p style="color: blue; font-size: 18px;">This is a paragraph with inline CSS.</p>
```

---

### 📄 2. **Internal CSS**
CSS is written inside a `<style>` tag in the `<head>` section of the HTML file.

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    h1 {
      color: green;
      text-align: center;
    }
  </style>
</head>
<body>

<h1>This heading uses internal CSS</h1>

</body>
</html>
```
---

### ✅ Internal CSS with ID and Class

```html
<!DOCTYPE html>
<html>
<head>
  <style>
    /* Class selector - starts with a dot (.) */
    .highlight {
      color: orange;
      font-weight: bold;
    }

    /* ID selector - starts with a hash (#) */
    #special {
      color: blue;
      font-size: 20px;
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <h2 class="highlight">This heading uses a class selector (highlight).</h2>

  <p>This is a normal paragraph.</p>

  <p id="special">This paragraph uses an ID selector (special).</p>

</body>
</html>
```

---

### 🧠 Quick Notes:
- **Class** is reusable. You can apply it to multiple elements.
- **ID** should be unique for each page. It’s used when you want to target a single specific element.

---

### 📁 3. **External CSS**
CSS is written in a separate `.css` file and linked to the HTML file using `<link>`.

#### ➤ `style.css` (external file)
```css
body {
  background-color: #f0f0f0;
  font-family: Arial, sans-serif;
}

p {
  color: darkred;
  font-size: 16px;
}
```

#### ➤ `index.html` (linking the CSS)
```html
<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>

<p>This paragraph is styled using external CSS.</p>

</body>
</html>
```

---

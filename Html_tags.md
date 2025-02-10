# 🔹 HTML Tags List with Examples

HTML (**HyperText Markup Language**) uses **tags** to define the structure and content of a webpage. Tags are enclosed in angle brackets (`< >`) and usually come in **pairs**:

📌 **Opening Tag** → `<tag>`  
📌 **Closing Tag** → `</tag>`  

---

## 📌 Basic HTML Structure

```html
<!DOCTYPE html>
<html>
<head>
    <title>My First Webpage</title>
</head>
<body>
    <h1>Welcome to My Website</h1>
    <p>This is a paragraph.</p>
</body>
</html>
```

---

## 🔥 Common HTML Tags and Their Uses

### 🔹 1️⃣ Basic Structure Tags

| Tag | Description | Example |
|------|------------|---------|
| `<html>` | Root element | `<html>...</html>` |
| `<head>` | Contains metadata | `<head>...</head>` |
| `<title>` | Defines page title | `<title>My Website</title>` |
| `<body>` | Main content | `<body>...</body>` |

---

### 🔹 2️⃣ Heading Tags (`<h1>` - `<h6>`) 

- Used for headings; `<h1>` is the largest, `<h6>` is the smallest.

```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Section Title</h3>
```

---

### 🔹 3️⃣ Text Formatting Tags

| Tag | Description | Example |
|------|------------|---------|
| `<p>` | Paragraph | `<p>This is a paragraph.</p>` |
| `<b>` | Bold text | `<b>Bold Text</b>` |
| `<i>` | Italic text | `<i>Italic Text</i>` |
| `<u>` | Underline text | `<u>Underlined</u>` |
| `<strong>` | Important (bold) | `<strong>Important!</strong>` |
| `<em>` | Emphasized (italic) | `<em>Emphasized</em>` |
| `<mark>` | Highlighted text | `<mark>Highlight</mark>` |

---

### 🔹 4️⃣ List Tags

| Type | Tag | Example |
|------|------|---------|
| **Unordered List** | `<ul>` | `<ul><li>Item 1</li><li>Item 2</li></ul>` |
| **Ordered List** | `<ol>` | `<ol><li>First</li><li>Second</li></ol>` |
| **List Item** | `<li>` | `<li>Item</li>` |

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
</head>
<body>

    <h2>Unordered List</h2>
    <ul>
        <li>Apple</li>
        <li>Banana</li>
        <li>Cherry</li>
    </ul>

    <h2>Ordered List</h2>
    <ol>
        <li>Step 1: Turn on the computer</li>
        <li>Step 2: Open the browser</li>
        <li>Step 3: Search for information</li>
    </ol>

    <h2>Nested List</h2>
    <ul>
        <li>Fruits
            <ul>
                <li>Apple</li>
                <li>Banana</li>
            </ul>
        </li>
        <li>Vegetables
            <ul>
                <li>Carrot</li>
                <li>Broccoli</li>
            </ul>
        </li>
    </ul>

</body>
</html>
```

---

### 🔹 5️⃣ Link & Image Tags

| Tag | Description | Example |
|------|------------|---------|
| `<a>` | Hyperlink | `<a href="https://google.com">Google</a>` |
| `<img>` | Image | `<img src="image.jpg" alt="My Image">` |
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hyperlink and Image Example</title>
</head>
<body>

    <h1>Hyperlink Example</h1>
    <p>Click the link below to visit Google:</p>
    <a href="https://google.com" target="_blank">Google</a>

    <h1>Image Example</h1>
    <p>Below is an image:</p>
    <img src="image.jpg" alt="My Image" width="300">

</body>
</html>

```
---

### 🔹 6️⃣ Table Tags

| Tag | Description | Example |
|------|------------|---------|
| `<table>` | Defines a table | `<table>...</table>` |
| `<tr>` | Table row | `<tr>...</tr>` |
| `<td>` | Table data | `<td>Data</td>` |
| `<th>` | Table header | `<th>Heading</th>` |

```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Table Example</title>
</head>
<body>

    <h1>Simple Table</h1>

    <table border="1">
        <tr>
            <th>ID</th>
            <th>Name</th>
            <th>Age</th>
            <th>City</th>
        </tr>
        <tr>
            <td>1</td>
            <td>Rahul</td>
            <td>25</td>
            <td>Delhi</td>
        </tr>
        <tr>
            <td>2</td>
            <td>Anjali</td>
            <td>22</td>
            <td>Mumbai</td>
        </tr>
        <tr>
            <td>3</td>
            <td>Amit</td>
            <td>28</td>
            <td>Kolkata</td>
        </tr>
    </table>

</body>
</html>

```

---

### 🔹 7️⃣ Form Tags (Input & Forms)

| Tag | Description | Example |
|------|------------|---------|
| `<form>` | Defines a form | `<form>...</form>` |
| `<input>` | Input field | `<input type="text">` |
| `<button>` | Button | `<button>Click Me</button>` |
| `<textarea>` | Multi-line input | `<textarea></textarea>` |
| `<label>` | Label for input | `<label>Name:</label>` |

```html
<form>
    <label>Name:</label>
    <input type="text">
    <button type="submit">Submit</button>
</form>
```

---

### 🔹 8️⃣ Div & Span (Layout Tags)

| Tag | Description | Example |
|------|------------|---------|
| `<div>` | Block-level container | `<div>Content</div>` |
| `<span>` | Inline container | `<span>Text</span>` |

```html
<div style="background:lightblue; padding:10px;">
    <h2>Section</h2>
    <p>Some text here.</p>
</div>
```

---

### 🔹 9️⃣ Media Tags

| Tag | Description | Example |
|------|------------|---------|
| `<video>` | Embeds video | `<video controls><source src="video.mp4"></video>` |
| `<audio>` | Embeds audio | `<audio controls><source src="audio.mp3"></audio>` |
| `<iframe>` | Embed another page | `<iframe src="https://example.com"></iframe>` |

---



✅ **HTML tags structure a webpage**  
✅ **They define headings, paragraphs, images, links, tables, forms, and more**  
✅ **Used together with CSS & JavaScript for complete web design**  
 😊

Here’s a simple **navbar** using **HTML** and **external CSS**:

---

### 🔹 `index.html`
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Simple Navbar</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav class="navbar">
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#">About</a></li>
      <li><a href="#">Services</a></li>
      <li><a href="#">Contact</a></li>
    </ul>
  </nav>

</body>
</html>
```

---

### 🔹 `style.css`
```css
body {
  margin: 0;
  font-family: Arial, sans-serif;
}

.navbar {
  background-color: #333;
  padding: 10px 0;
}

.navbar ul {
  list-style: none;
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
}

.navbar li {
  margin: 0 15px;
}

.navbar a {
  color: white;
  text-decoration: none;
  font-weight: bold;
}

.navbar a:hover {
  text-decoration: underline;
}
```

---

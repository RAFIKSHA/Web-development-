### 🚀 **Step 1: JavaScript Basics**  

JavaScript is a **client-side scripting language** used to make **web pages dynamic and interactive**.  

---

## **1️⃣ JavaScript Introduction & Setup**
### 🔹 **How Does JavaScript Work?**  
- JavaScript is written inside an **HTML page** using the `<script>` tag.  
- It is executed by the **web browser**.  
- It can also be written in a **separate `.js` file** and linked to the HTML.  

### 🔹 **3 Ways to Add JavaScript**  
✅ **1. Internal JavaScript (Inside HTML Page)**  
```html
<!DOCTYPE html>
<html>
<head>
    <title>JavaScript Example</title>
</head>
<body>
    <h1>Welcome to JavaScript</h1>
    <script>
        alert("Hello, JavaScript!");
    </script>
</body>
</html>
```
This will show an **alert box** when the page loads.

✅ **2. External JavaScript (Separate `.js` file)**
```html
<!DOCTYPE html>
<html>
<head>
    <title>External JavaScript</title>
    <script src="script.js"></script>
</head>
<body>
    <h1>JavaScript External File Example</h1>
</body>
</html>
```
👉 **Inside `script.js` file:**
```js
alert("This is an external JavaScript file!");
```

✅ **3. Inline JavaScript (Directly inside HTML tag - Not Recommended)**
```html
<button onclick="alert('Button Clicked!')">Click Me</button>
```

---

## **2️⃣ JavaScript Syntax & Comments**
### 🔹 **JavaScript Syntax**
JavaScript **statements (instructions)** are written using a semicolon (`;`).  
```js
console.log("Hello, JavaScript!"); // Output: Hello, JavaScript!
```
> **Note:** The semicolon (`;`) is optional but recommended.

### 🔹 **JavaScript Comments**
✅ **Single-line Comment** (`//`)
```js
// This is a single-line comment
console.log("Hello, World!"); // Output: Hello, World!
```
✅ **Multi-line Comment** (`/* */`)
```js
/*  
This is a multi-line comment  
It can span multiple lines  
*/
console.log("Welcome to JavaScript!");
```

---

## **3️⃣ JavaScript Variables (var, let, const)**
A **variable** is a container for storing data values.  

### 🔹 **Three Ways to Declare Variables**  
| Keyword | Scope | Can be Reassigned? | Block Scope? |
|---------|-------|-------------------|--------------|
| `var`   | Function | ✅ Yes | ❌ No |
| `let`   | Block | ✅ Yes | ✅ Yes |
| `const` | Block | ❌ No (Cannot Change Value) | ✅ Yes |

✅ **`var` (Old method, Avoid if possible)**  
```js
var name = "Shah";
console.log(name); // Output: Shah

var name = "Rafik"; // Re-declaration allowed
console.log(name); // Output: Rafik
```

✅ **`let` (Modern & Recommended)**
```js
let age = 25;
console.log(age); // Output: 25

age = 26; // Allowed (Value Change)
console.log(age); // Output: 26
```

✅ **`const` (Cannot Change Value)**
```js
const PI = 3.1416;
console.log(PI); // Output: 3.1416

// PI = 3.14; ❌ Error: Assignment to constant variable
```

---

## **4️⃣ JavaScript Data Types**
JavaScript has **two main types** of data:  
1️⃣ **Primitive Data Types (Basic)**  
2️⃣ **Non-Primitive Data Types (Complex)**  

### 🔹 **1. Primitive Data Types (Single Value)**
| Data Type | Example |
|-----------|---------|
| `String` | `"Hello"` |
| `Number` | `123`, `10.5` |
| `Boolean` | `true`, `false` |
| `Undefined` | `let x;` |
| `Null` | `let y = null;` |

```js
let name = "Shah"; // String
let age = 25;      // Number
let isStudent = true; // Boolean
let x; // Undefined
let y = null; // Null
console.log(typeof name, typeof age, typeof isStudent, typeof x, typeof y);
```
> **`typeof` Operator** tells the data type of a variable.

### 🔹 **2. Non-Primitive Data Types (Complex)**
| Data Type | Example |
|-----------|---------|
| `Array` | `["Apple", "Banana", "Orange"]` |
| `Object` | `{name: "Shah", age: 25}` |

```js
// Array Example
let fruits = ["Apple", "Banana", "Orange"];
console.log(fruits[0]); // Output: Apple

// Object Example
let person = {
    name: "Shah",
    age: 25
};
console.log(person.name); // Output: Shah
```

---

## **5️⃣ JavaScript Operators**
JavaScript includes **Arithmetic, Comparison, Logical, Assignment, and String Operators**.

### 🔹 **1. Arithmetic Operators**
| Operator | Example | Output |
|----------|---------|--------|
| `+` | `5 + 3` | `8` |
| `-` | `10 - 4` | `6` |
| `*` | `4 * 3` | `12` |
| `/` | `10 / 2` | `5` |
| `%` | `10 % 3` | `1` |
| `++` | `let a = 5; a++` | `6` |
| `--` | `let b = 5; b--` | `4` |

```js
let a = 10, b = 5;
console.log(a + b); // Output: 15
console.log(a % b); // Output: 0
```

### 🔹 **2. Comparison Operators**
| Operator | Example | Output |
|----------|---------|--------|
| `==` | `5 == "5"` | `true` (Only value comparison) |
| `===` | `5 === "5"` | `false` (Value + Type comparison) |
| `!=` | `10 != 5` | `true` |
| `!==` | `10 !== "10"` | `true` |
| `>` | `10 > 5` | `true` |
| `<` | `5 < 10` | `true` |

```js
console.log(5 == "5");  // true
console.log(5 === "5"); // false
console.log(10 > 5);    // true
```

---
# **📌 JavaScript Conditional Statements & Loops**  

In JavaScript, **Conditional Statements** are used for decision-making, and **Loops** are used for repeated execution. Let’s explore them one by one.  

---

## **✅ 1. Conditional Statements**  

### **🔹 if-else Statement**
```js
let num = 10;
if (num > 0) {
    console.log("Number is positive");
} else {
    console.log("Number is not positive");
}
```
✔ **If the condition is true, the code inside `if` runs. Otherwise, the `else` block runs.**  

---

### **🔹 if-else if-else (Multiple Conditions)**
```js
let num = -5;
if (num > 0) {
    console.log("Positive number");
} else if (num < 0) {
    console.log("Negative number");
} else {
    console.log("Number is zero");
}
```
✔ **Checks multiple conditions one by one.**  

---

### **🔹 switch-case (Alternative to if-else)**
```js
let day = 3;
switch (day) {
    case 1:
        console.log("Monday");
        break;
    case 2:
        console.log("Tuesday");
        break;
    case 3:
        console.log("Wednesday");
        break;
    default:
        console.log("Invalid day");
}
```
✔ **Each `case` is checked, and when a match is found, the corresponding block runs.**  
✔ **Use `break` to stop execution after a case is matched.**  

---

## **✅ 2. Loops in JavaScript**  

Loops allow you to execute a block of code multiple times.

---

### **🔹 for Loop (Fixed Repetitions)**
```js
for (let i = 1; i <= 5; i++) {
    console.log("Number:", i);
}
```
✔ **Runs from `i = 1` to `i = 5`, printing each number.**  

---

### **🔹 while Loop (Condition-Based)**
```js
let i = 1;
while (i <= 5) {
    console.log("Count:", i);
    i++;
}
```
✔ **Runs as long as the condition (`i <= 5`) is true.**  

---

### **🔹 do-while Loop (Runs at Least Once)**
```js
let i = 1;
do {
    console.log("Value:", i);
    i++;
} while (i <= 5);
```
✔ **Executes the block at least once, even if the condition is false.**  

---

## **🚀 Example: Combining Conditional Statements & Loops**
```js
for (let i = 1; i <= 10; i++) {
    if (i % 2 === 0) {
        console.log(i + " is even");
    } else {
        console.log(i + " is odd");
    }
}
```
✔ **Prints even and odd numbers from 1 to 10 using a loop and `if-else`.**  

---

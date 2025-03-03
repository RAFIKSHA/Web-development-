---

## **🔹 1. `alert()` - Simple Alert Message**
✅ **Ye ek simple pop-up message show karta hai.**
```html
<button onclick="alert('Hello, Welcome!')">Click Me</button>
```
📝 **Use:** Warnings ya notifications ke liye.

---

## **🔹 2. `console.log()` - Console me Output Show Karna**
✅ **Ye browser ke console me message print karta hai.**
```html
<button onclick="console.log('Button Clicked!')">Click Me</button>
```
🔎 **Console Check Karne Ke Liye:**  
- Right Click → Inspect → Console  
- Yaha pe `Button Clicked!` print hoga.

📝 **Use:** Debugging aur testing ke liye.

---

## **🔹 3. `document.write()` - Page Me Direct Text Show Karna**
✅ **Ye directly HTML page me text likhne ke liye use hota hai.**
```html
<button onclick="document.write('Hello, World!')">Click Me</button>
```
⚠️ **Warning:** Ye pura page ka content overwrite kar deta hai.

📝 **Use:** Simple testing ke liye (Lekin real-world me use nahi karna chahiye).

---

## **🔹 4. `prompt()` - User Se Input Lena**
✅ **Ye ek pop-up box open karta hai jisme user input dal sakta hai.**
```html
<button onclick="askName()">Enter Name</button>

<script>
    function askName() {
        let name = prompt("Enter your name:");
        alert("Hello, " + name + "!");
    }
</script>
```
📝 **Use:** Jab user se input lena ho.

---

## **🔹 5. `confirm()` - Yes/No Confirmation Dena**
✅ **Ye ek confirmation box show karta hai jisme "OK" aur "Cancel" buttons hote hain.**
```html
<button onclick="confirmAction()">Delete Item</button>

<script>
    function confirmAction() {
        let result = confirm("Are you sure you want to delete?");
        if (result) {
            alert("Item Deleted!");
        } else {
            alert("Action Cancelled.");
        }
    }
</script>
```
📝 **Use:** Jab kisi action ka confirmation lena ho.

---

## **🔹 6. `setTimeout()` - Delay Ke Saath Function Run Karna**
✅ **Ye function ek set time ke baad execute hota hai.**
```html
<button onclick="delayedMessage()">Show Message After 3 Sec</button>

<script>
    function delayedMessage() {
        setTimeout(function() {
            alert("This message appears after 3 seconds!");
        }, 3000);
    }
</script>
```
📝 **Use:** Delay ke saath actions execute karne ke liye.

---

## **🔹 7. `setInterval()` - Repeat Function Every Few Seconds**
✅ **Ye function har kuch seconds ke interval pe repeat hota hai.**
```html
<button onclick="startClock()">Start Clock</button>
<p id="clock"></p>

<script>
    function startClock() {
        setInterval(function() {
            let time = new Date().toLocaleTimeString();
            document.getElementById("clock").innerHTML = time;
        }, 1000);
    }
</script>
```
📝 **Use:** Real-time clocks ya repeated actions ke liye.

---

## **🔹 8. `document.getElementById().innerHTML` - HTML Content Change Karna**
✅ **HTML element ka content dynamically change karna.**
```html
<button onclick="changeText()">Change Text</button>
<p id="demo">Old Text</p>

<script>
    function changeText() {
        document.getElementById("demo").innerHTML = "New Text Updated!";
    }
</script>
```
📝 **Use:** Web page content dynamically update karne ke liye.

---

## **🔹 9. `window.open()` - New Tab Open Karna**
✅ **Ye ek new tab ya window open karta hai.**
```html
<button onclick="openGoogle()">Open Google</button>

<script>
    function openGoogle() {
        window.open("https://www.google.com", "_blank");
    }
</script>
```
📝 **Use:** New tab ya external links open karne ke liye.

---

## **🔹 10. `window.close()` - Window Close Karna**
✅ **Ye current tab ko close karne ke liye use hota hai.**
```html
<button onclick="closeWindow()">Close Tab</button>

<script>
    function closeWindow() {
        window.close();
    }
</script>
```
⚠️ **Note:** Ye function tabhi kaam karega jab page JavaScript ke through open kiya ho.

---

## **🎯 Conclusion**
Aapko ab JavaScript ke **different functions** ka idea mil gaya hoga. Ye sabhi functions **user interaction, debugging aur dynamic web pages** ke liye use hote hain.

✅ **Sabse Useful Functions:**
1. `alert()` - Notification dene ke liye  
2. `console.log()` - Debugging ke liye  
3. `prompt()` - User se input lene ke liye  
4. `confirm()` - Action confirm karne ke liye  
5. `document.write()` - Simple testing ke liye  
6. `document.getElementById().innerHTML` - Page content change karne ke liye  
7. `setTimeout()` - Delay ke liye  
8. `setInterval()` - Repeated actions ke liye  
9. `window.open()` - New tab open karne ke liye  
10. `window.close()` - Tab close karne ke liye  

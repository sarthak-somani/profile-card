# The Simple CSS Cheatsheet

CSS (Cascading Style Sheets) is the "clothing" of your webpage. It's how you add style, color, and layout.

### **How CSS Works: Selectors**

You use "selectors" to target HTML elements. The most common are:
* **Tag Selector:** Targets all elements of a type. `p { color: blue; }`
* **Class Selector:** Targets all elements with a specific `class="..."`. Starts with a dot. `.card { background-color: white; }`
* **ID Selector:** Targets one specific element with an `id="..."`. Starts with a hash. `#main-title { font-size: 40px; }`

### **The Basics**

```css
/* Inside a selector like .my-element { ... } */
color: #ff5733;                 /* Text color */
background-color: #2c3e50;      /* Background color */
font-family: 'Georgia', serif;  /* Font style */
font-size: 18px;                /* Text size */
text-align: center;             /* left, right, center */
```
**Tip:** Head over to [Adobe Color Wheel](https://color.adobe.com/create/color-wheel) to explore and create color palettes and get the corresponding HEX codes.


### **The Box Model (Spacing)**

Every element is a box.
* `padding: 20px;` - Space **inside** the box (between content and border).
* `margin: 15px;` - Space **outside** the box (between this box and others).
* `border: 2px solid #333;` - A border around the box.

### **Sizing and Shape**

* `width: 400px;`
* `height: 250px;`
* `border-radius: 15px;` - The magic for rounded corners. `50%` makes a circle!

---

### **Intermediate Magic: Make it Interactive!**

* **Shadows (`box-shadow`):** Adds depth to your elements.
    ```css
    /* Syntax: horizontal-offset | vertical-offset | blur-radius | color */
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.2);
    ```

* **Hover Effects (`:hover`):** Change styles when the mouse is over an element. This is key for making buttons feel alive.
    ```css
    .social-links a:hover {
      background-color: #007bff; /* A nice blue */
      color: white;
    }
    ```

* **Smooth Transitions (`transition`):** Makes hover effects smooth instead of instant. Add this to the *original* element (not the `:hover` part).
    ```css
    .social-links a {
      /* Add this line to your existing styles */
      transition: background-color 0.3s ease;
    }
    ```

### **Advanced Zone: For the Adventurous!**

* **Gradients:** Use an online tool like [cssgradient.io](https://cssgradient.io/) to generate the code and use it for `background`.
    ```css
    background: linear-gradient(to right, #ff7e5f, #feb47b);
    ```

* **Transforms:** Move, scale, or rotate elements, often used with `:hover`.
    ```css
    .card:hover {
      /* This makes the card lift up and get slightly bigger on hover! */
      transform: translateY(-10px) scale(1.03);
      transition: transform 0.3s ease; /* Don't forget the transition! */
    }
    ```

---

### Your Turn!

Let your creativity run free :)
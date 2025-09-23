# The Simple HTML Cheatsheet

HTML (HyperText Markup Language) is the skeleton of your webpage. It's made of "tags". Most tags have an opening `<tag>` and a closing `</tag>`.

### **Core Text Elements**

* **Headings:** For titles and subtitles.
    ```html
    <h1>This is a very big title</h1>
    <h2>This is a slightly smaller title</h2>
    <h6>This is the smallest title</h6>
    ```
* **Paragraphs:** For regular text.
    ```html
    <p>This is a paragraph of text. You can write as much as you want here.</p>
    ```
* **Emphasis:** To make text stand out.
    ```html
    <p>This text is normal, but <strong>this part is bold</strong> and <em>this part is italic.</em></p>
    ```

### **Lists**

Perfect for adding your skills, hobbies, or favorite courses!

* **Unordered List (bullets):**
    ```html
    <ul>
      <li>Python</li>
      <li>Web Development</li>
      <li>Robotics</li>
    </ul>
    ```
* **Ordered List (numbers):**
    ```html
    <ol>
      <li>First item</li>
      <li>Second item</li>
      <li>Third item</li>
    </ol>
    ```

### **Links**

The `<a>` tag (anchor tag) creates clickable links. The `href` attribute is the destination.
```html
<a href="https://wncc.tech-iitb.org/">Visit the WnCC Website</a>
```

### **Images**

The `<img>` tag is self-closing.
* `src` is the source of the image (a URL or a local file).
* `alt` is the alternative text, important for accessibility.

```html
<img src="wncc-logo.png" alt="The WnCC Bombay Logo">
```

### **Containers (The `<div>`)**

A `<div>` is like an invisible box you can use to group elements together. This is super useful for styling. Notice how our entire profile card is wrapped in `<div class="card">`. The `class` attribute gives the box a name so you can style it in CSS.

---

### **Your Turn! Ideas to Try:**

1.  Add an unordered list (`<ul>`) of your top 3 skills or hobbies under your bio.
2.  Change the text of the social links and add your own.
3.  Add another paragraph (`<p>`) with your favorite quote.
4. Let your imagination run free :)
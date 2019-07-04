# HTML, CSS, and Javascript for Web Developers

by Johns Hopkins University

## WEEK 1
###Environment Setting
---

- broswer-sync

```bash
sudo npm install -g browser-sync
```

- node.js

```
https://nodejs.org/en/
```

- version check 

```bash
echo $PATH
node --version
browser-sync --version
```

- Generate commands

```bash
browser-sync --server --directory --files "*"
echo $PATH
```
**Useful Websites**
- [jsfiddle](https://jsfiddle.net/)
- [codepen](https://codepen.io/)
- [css-tricks](https://css-tricks.com/)
- [caniuse](https://caniuse.com/)
- [w3validator](https://validator.w3.org)

###Tags
---
`<h1>`			: Header 
`<p>`				: Paragraph
`<title>`		: Title
`<body>`		: Body
`<nav>`			: Navigation, usually linkes to other parts of the website
`<section>`	: Section tag, usually with a subtag of `<artical>`
`<articl>`	: Article
`<aside>`		: Some information that relates tot he main topic, i.e., related posts.

###Lists
---
**Unordered List**
```html
<body>
  <h1>Unordered list</h1>
  <div>
    My typical dinner shopping list:
    <ul>
      <li>Milk</li>
      <li>Donuts</li>
      <li>Cookies
        <ul>
          <li>Chocolate</li>
          <li>Sugar</li>
          <li>Peanut Butter</li>
        </ul>
      </li>
      <li>Pepto Bismol</li>
    </ul>
  </div>
```
**Ordered List**
```html
  <div>
    Oreo cookie eating procedure:
    <ol>
      <li>Open box</li>
      <li>Take out cookie</li>
      <li>Make a Double Oreo
        <ol>
          <li>Peel off the top part</li>
          <li>Place another cookie in the middle</li>
          <li>Put back the top part</li>
        </ol>
      </li>
      <li>Enjoy!</li>
    </ol>
  </div>
```

###HTML Character Entity References
---
Actions | Represented in HTML
:-- | --- 
< | `&lt;`
> | `&gt;`
& | `&amp;`
&copy; | `&copy;`
non breaking space | `&nbsp;`
""|`&quot;`

###Create Links
---
**The`a`element**
-	Flow content
-	Phrasing content
-	Interactive content
-	Palpable content

**Internal Link**
```html
    <a href="same-directory.html" title="same dir link">Linking to a file in the same directory</a>
```
or
```html
    <a href="same-directory.html" title="same dir link">
      <div> DIV Linking to a file in the same directory</div>
    </a>
```

**External Link**
```html
<a href="http://www.facebook.com/CourseraWebDev" 
target="_blank" title="Like Our Page!">Course Facebook Page</a>
```
- `_blank`: open a new tab to the new page

**Same Page Link**
```html
    <ul>
      <!-- Link to every section in the page -->
      <li><a href="#section1">#section1</a></li>
      <li><a href="#section2">#section2</a></li>
      <li><a href="#section3">#section3</a></li>
    </ul>
```

**Same Directory Link**

```html
  <h1>Same directory as links-internal.html</h1>
  <a href="links-internal.html" title="Back to internal links page">Back to links-internal.html</a>
```

**Displaying Images**
```html
<img src="picture-with-quote.jpg" width="400" height="235" alt="Picture with a quote">
```
```html
<img src="http://lorempixel.com/output/nature-q-c-640-480-1.jpg" width="640" height="480">
```



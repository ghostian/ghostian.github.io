# HTML, CSS, and Javascript for Web Developers

by Johns Hopkins University

## WEEK 2

### Useful commands

---

```css
font-size: 24px;
font-weight: bold;
background-color: red;
opacity: .7;
font-style: italic;
text-align: center;
```

### Anatomy of a CSS Rule

---

```css
p {
    color: red;
    font-size: 20px;
    width: 50px;
  }
```

### Element, Class, and ID Selectors

---

#### Elements Selectors

```css
/* all p AND h1 elements */
p, h1 {
  color: blue;
  text-align: center;
}
```

```html
<h1>Simple Selectors (h1)</h1>
<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Eligendi nemo ipsum dolores vel modi magnam veniam alias at nam. Voluptatem officiis dolor dolorem aspernatur dolorum modi ipsa, nobis animi aut!</p>
```

#### Class Selectors

```css
/* all with class="highlight" */
.highlight {
  font-size: 20px;
  font-weight: bold;
  font-style: italic;
  background-color: green;
  opacity: .6;
}
```

```html
<p class="highlight">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Possimus amet alias est? Nobis cum quasi at soluta odit, maiores quaerat dolores expedita ex nemo ea repellendus dolorem sed maxime quos?</p>
```

#### ID Selectors

```css
/* element with id="mainPoint" */
#mainPoint {
  font-size: 24px;
  font-weight: bold;
  background-color: red;
  opacity: .7;
}
```

```html
<span id="mainPoint">id="mainPoint".</span> </div>
```

#### Group Selectors

```css
div, .blue{
  color: blue
}
```

### Combining Selectors

#### Element with class selector

```css
p.big{
  font-size: 20px;
}
```

#### Child Selector

```css
article > p {
  color: blue;
}
```

It will effect the structure like this:

```html
<article>
  <p> ... </p>
</article>  
```

Every **p** element is a **direct** child of **article**.

#### Descendant Selector

```css
article p{
  color: blue;
}
```

Every **p** element is a **inside** **article**.

### Pseudo-Class Selectors

``` css

/* Styles go here. */
header li {
  list-style: none;
}
a:link, a:visited {
  text-decoration: none;
  background-color: green;
  border: 1px solid blue;
  color: black;
  display: block;
  width: 200px;
  text-align: center;
  margin-bottom: 1px;
}
a:hover, a:active {
  background-color: red;
  color: purple;
}
header li:nth-child(3) {
  font-size: 24px;
}
section div:nth-child(odd) {
  background-color: gray;
}
section div:nth-child(4):hover {
  background-color: green;
  cursor: pointer;
}

```

---
published: true
excerpt: HTML tutorial 3
toc: true
toc_label: My Table of Contents
toc_icon: cog
---
How html content is displayed in dictated by CSS. This is made up of the selector, example p, and the declaration which is made of the property and value. The property and value are separated by and colon and each declaration must be separated by a semi-colon. CSS uses curly brackets and can be specified in three ways

**1.** As a separate CSS folder and then referenced in the html using "a href". 

**2.** Style is specified in the head between the styles tags. See Example Section 1 below

**3.** Within the opening tag of the selector. Emaple below


```html
<p color: red; font size: 20px;> This is a test </p>
```
<p style="color: red; font-size: 20px;">
This is a test
</p>


### Section 1 - ID tag with # in css

This is between the <head></head> tags 
```css
<title>CSS Rule</title>
<style>
#para1 {
  color: red;
  font-size: 20px;
}

h2 {
  color: black;
  font-size: 36px;
  text-align: center;
}
</style>
```
The content is between the <body></body> tags 

```html
<body>
<h2> CSS Rules</h2>
<h3>Subheading 1</h3>
<p id="para1">How html content is displayed in dictated by CSS.</p>
<h3>Subheading 2</h3>
<p>The property and value are separated by and colon and each declaration must be separated by a semi-colon. </p>
</body>

```

<title>CSS Rule</title>
<style>
#para1 {
  color: red;
  font-size: 20px;
}

h2 {
  color: black;
  font-size: 36px;
  text-align: center;
}
</style>

<h2> CSS Rules</h2>
<h3>Subheading 1</h3>
<p id="para1">How html content is displayed in dictated by CSS.</p>
<h3>Subheading 2</h3>
<p>The property and value are separated by and colon and each declaration must be separated by a semi-colon. </p>



### section 2 - class with "." in css



### section 3 - selecting direct child tags

### section 4 - select all tags inside 

### section 5 - pseudo selectors (on hover)
```
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
```

---
published: true
excerpt: Welcome to my blog
toc: true
toc_label: My Table of Contents
toc_icon: cog
---


Hello! and welcome to my blog. This blog, and many others, are my notes and what helped me while I was learning new skills related to website design. I was drowning in information and had to carefully pick out the things that helped me in my journey to become a web developer. I am signed up for an [associates degree at Los Rios College](https://www.scc.losrios.edu/academics/programs-and-majors/computer-information-science) for Web Developer.

I also took some online courses which helped me. I followed a course on [coursera](https://www.coursera.org/learn/html-css-javascript-for-web-developers/home/welcome) and 
the [course lectures](https://github.com/eshanis/fullstack-course4) and code can be found on github

Another online course that was interactive and helped me was [rithm school](https://www.rithmschool.com/courses/html-css-fundamentals) 
The Code and lectures for this course can be found [here](https://github.com/eshanis/html_css_basics_solutions)

An awesome code editor I used was, [Brackets](http://brackets.io/), which lets me view my changes live and also lets me find my CSS code directly when I highlight my HTML code.

![]({{site.baseurl}}/assets/images/brackets_edit.PNG)


### MY NOTES

html tags

### 1. html tags always have an opening tag and closing tag and the content is between these tags
   example:
```
<!doctype html>
<!--this is an opening tag-->
<html>
<head>
  <meta charset="utf-8">
  <title>div and span elements</title>
</head>
<body>
  <div>*** DIV 1: Some content here ***</div>
  <div>*** DIV 2: Following right after div 1 ***</div>
  <span>*** SPAN 1: Following right after div 2 ***</span>
  <div>
    *** DIV 3: Following right after span 1 
    <span>*** SPAN 2: INSIDE div 3 ***</span>
    Continue content of div 3 ***
  </div>
</body>
<!--this is an closing tag-->
</html>
``` 

  <div>*** DIV 1: Some content here ***</div>
  <div>*** DIV 2: Following right after div 1 ***</div>
  <span>*** SPAN 1: Following right after div 2 ***</span>
  <div>
    *** DIV 3: Following right after span 1 
    <span>*** SPAN 2: INSIDE div 3 ***</span>
  <span>*** SPAN 3 on same line as span 2 ***</span>
    Continue content of div 3 ***
  </div>





### 2. some tags don't have a closing tag 
examples:

```
<!--this is line break-->
<br>
<!--this is horizontal line-->
<hr>  
```
<hr>  
<br>
<br>
<hr>


### 3. html text ranges form h1, largest to h6, smallest

```
<h1>This is the Main Heading</h1>
  <h2>Subheading 2</h2>
  <h3>Subheading 3</h3>
  <h4>Subheading 4</h4>
  <h5>Subheading 5</h5>
  <h6>Subheading 6</h6>

```

<body>
  <h1>This is the Main Heading</h1>
  <h2>Subheading 2</h2>
  <h3>Subheading 3</h3>
  <h4>Subheading 4</h4>
  <h5>Subheading 5</h5>
  <h6>Subheading 6</h6>
</body>



### 4. Sections, articles, header and footer

```
<header>
    header element - Some header information goes here. Usually consists of company logo, some tag line, etc. Sometimes, navigation is contained in the header as well.
    <nav>nav (short for navigation) element - Usually contains links to different parts of the web site.</nav>
  </header>
  <h1>Main Heading of the Page (hard not to have it)</h1>
  <section>
    Section 1
    <article>Article 1</article>
    <article>Article 2</article>
    <article>Article 3</article>
  </section>
  <section>
    Section 2
    <article>Article 4</article>
    <article>Article 5</article>
    <article>Article 6</article>
    <div>Regular DIV element</div>
  </section>
  <aside>
    ASIDE - Some information that relates to the main topic, i.e., related posts.
  </aside>

  <footer>
    JHU Copyright 2015
  </footer>
  
  ```

  </header>
  <h1>Main Heading of the Page (hard not to have it)</h1>
  <section>
    Section 1
    <article>Article 1</article>
    <article>Article 2</article>
    <article>Article 3</article>
  </section>
  <section>
    Section 2
    <article>Article 4</article>
    <article>Article 5</article>
    <article>Article 6</article>
    <div>Regular DIV element</div>
  </section>
  <aside>
    ASIDE - Some information that relates to the main topic, i.e., related posts.
  </aside>

  <footer>
    JHU Copyright 2015
  </footer>

### 5. ordered list

```
<body>
  <h1>Ordered list</h1>
  <div>
    Oreo cookie eating procedure:
    <ol>
      <li>Open box</li>
      <li>Take out cookie</li>
      <li>Make a Double Oreo
        <!-- below is an ordered list within a list item -->   
        <ol>
          <li>Peel off the top part</li>
          <li>Place another cookie in the middle</li>
          <li>Put back the top part</li>
        </ol>
         <!-- end of ol within the li -->   
      </li>
      <li>Enjoy!</li>
    </ol>
  </div>
</body>
```


  <h1>Ordered list</h1>
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



**NOTE :### Commenting in CSS file**
to comment any line in CSS file use "/*"

```
li
{ 
    /* 
	list-style: none;
    */
}

```

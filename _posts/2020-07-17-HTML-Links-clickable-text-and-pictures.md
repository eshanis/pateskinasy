---
published: true
Published: true
thumbnail: /assets/images/bio-photo.jpg
title: Learn about links
excerpt: Hyperlinked images text
---

### Sometimes you want to put links to others people's pages or pages within your own website.
For this, you use the "a" tags

**1. If you want to link to my github page**
```
<a href= "the_site_you_want_to_link"> The  Name of the site </a>
```

For example
```
 <a href="https://github.com/eshanis">  
    eshanis github Page      
 </a>
```

  <a href="https://github.com/eshanis">  
  eshani github Page      
  </a>
 
  <hr>
  
**2. Sometimes, you want to open the page in a new tab, so the user doesnt lose your page. Use "target=_blank"**
```
<a href= "the_site_you_want_to_link" target="_blank"> The  Name of the site you want to link to </a>
```

For example:
```
<!-- link to eshanis page WITH TARGET-->
<a href="https://github.com/eshanis"  target="_blank">      
	eshanis github Page       
</a>
```

  <a href="https://github.com/eshanis"  target="_blank">      
	eshanis github Page       
  </a>
  
  
  <hr>
  
**3. You may have noticed a title inside the opening "a" tag. This title shows up when you hover over the link**

For example:
```
  <!-- link to eshanis page WITH TITLE-->
<a href="https://github.com/eshanis"  target="_blank" title="star my github!">
eshanis github page
</a>       
```
 <a href="https://github.com/eshanis"  target="_blank" title="star my github!">
 eshanis github page
 </a>

**NOTE:** Hover over the above link to see the "title" text "star my github"
  <hr>
  
**4. In case you want to make an image as the thing you want the user to click to take them to another link**

For example
```
<a href="https://github.com/eshanis"  target="_blank" title="star my github!">
          <div>
            <img src="https://blog.eshani.ml/assets/images/eshu.jpg" alt="eshanis github page" width="100" height="100">
          </div>      
</a>

```

  <a href="https://github.com/eshanis"  target="_blank" title="star my github!">
  <img src="https://blog.eshani.ml/assets/images/eshu.jpg" alt="eshanis github page" width="100" height="100">
  </a>


**NOTE:** the use of "div" is optional.

   Hover over the image to see the "title" text "star my github"


  <hr>
  
**5. If you have many pages in your website and you want to link to another page in your website, you can do**

```
<a href="/html-tutorial1"  target="_blank" title="star my github!">
      
            <img src="https://blog.eshani.ml/assets/images/eshu.jpg" alt="eshani" width="100" height="100">
                
</a>
```
[tutorial 1](/html-tutorial1/)


**6.Linking to sections on the same page: fragment identifiers**



   <h1 id="top">Linking to Sections on The Same Page</h1>
   <div>Use the "id" tag at the section you want to link and "#" before the name when specifying "a href= ".</div>
   
   <div>When you click on "Section1", It takes you to the paragraph below that says "Section 1". </div> 
   <div>Example</div>
   
```
<ul>
<li><a href="#section1">Section1</a></li>
<li><a href="#section2">Section2</a></li>
```

```
<section id="section1">
<h3>Section 1</h3> 
<p> Mary Had a little lamb, little lamb, Little lamb. Mary had a little lamb whose fleece was whte as snow.
</section>
```
   
   <div>When you click on "back to top" at the bottom of the page, it takes you directly to the top of the page.        </div>
  
   
  Example:
    
```
<h1 id="top">Links to Sections on The Same Page</h1>   
```
```
<p>
Back to top: <a href="#top">Back to Top</a>
</p>
```
   
 <body>
    <h1 id="top">Try it for yourself :click on the section</h1>
  <section>
      <ul>
        <!-- Link to every section in the page -->
        <li><a href="#section1">Section1</a></li>
        <li><a href="#section2">Section2</a></li>
      </ul>
    </section>
  <br>
  <br>
  <br>
  <br>
  <hr>
  <br>

  <section id="section1">
      <h3>Section 1</h3> 
      <p> Mary Had a little lamb, little lamb, Little lamb. Mary had a little lamb whose fleece was white as snow.</p>
      </section>
  <br>
  <br>
  <br>
  <br>
  <hr>
  <br>

  <section id="section2"> 
      <h3>Section 2</h3>
      <p> Humpty Dumpty sat on a wall, Humpty Dumpty had a great fall. All the kings horses and all the kings men,      couldn't put humpty together again.</p>
  </section>
   <br>
   <br>
   <br>
   <br>
   <hr>
   <br> 
  <div>
   <p>
   Back to top: <a href="#top">Back to Top</a>
   </p>
   </div>
    <hr>
   </body>
   
 For detailed example [click here](https://github.com/eshanis/fullstack-course4/blob/master/examples/Lecture09/links-same-page.html)

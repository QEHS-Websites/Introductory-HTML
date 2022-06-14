# Introductory-HTML
Introductory HTML with inline CSS

**Purpose:** use a ReadMe.md file as a simply HTML Document to track changes and To Do Lists for a hosted webpage

**Purpose:** build simple webpages that are linked to each other, rendered in a browser, using HTML
- Full Listing of HTML Tags: https://www.w3schools.com/tags/default.asp

**Note:** Students have the option of local hosting or public hosting
- Local Hosting: only on one computer, entire Repo must be downloaded and all software must be confirgured same way
- Public Hosting: see GitHub Pages, <a href="https://github.com/QEHS-Websites/Website-Hosting">Click Here for additional notes</a>

---

Table of Contents
- Make simple changes to a ReadMe.md file (Hello World Repository in GitHub), then submit the URL so I can see your changes
- See below: Introduction to HTML5 using GitHub Markdown and Annotating Project Notes, <a href="https://github.com/QEHS-Websites/Introductory-HTML#introduction-to-html5-using-github-markdown">Click Here</a>
- HTML with inline CSS Boilerplate Checklist and Template Creation, <a href="https://github.com/QEHS-Websites/Introductory-HTML#html-with-inline-css-boilerplate-checklist-and-template-creation">
Click Here</a>
- For Notes, see https://github.com/QEHS-Websites/LearningHTML.github.io
- Note: a separate rubric exists for a "Website to Learn how to Write Websites"

Related Links
- See: https://github.com/MercersKitchen/Website-Mentoring
- See Dev Outreach Files (Must be compiled locally): https://github.com/Dev-Outreach/Introduction-Static-HTML

Additional Ideas
- Enrichment: <a href="https://github.com/QEHS-Websites/Introductory-HTML#enrichment-setting-up-the-chrome-browser-for-html--css-validation">
Setting up Validation for HTML and CSS in Chrome</a>

**JS Fiddle**: can be used to prototype all sections of a Webpage in a Chromebook

---

# Introduction to HTML5 using GitHub Markdown

**Note**: Can be done in any device

<a href="https://github.com/MercersKitchen/Markdown-ReadMe-Documentation">Click Here for Reference Repository by Mr. Mercer</a>

GitHub Markdown, with Additional HTML rendered in GitHub ReadMe.md files.
- Note, other programs use Markdown for formatting a variety of messages. Markdown is much easier to use if you are used to it or have a "Summary Sheet".
- "Opens a students world to a new type of formatting."
- "Project External Documentation"

Creating Single Page Applications (static or dynamic websites)
- Goal: host at least one through GitHub Website Hosting, further introduction to Google Analytics and Keywords to link to searches
- Using HTML & inline CSS
- "The front end of project promotion."

Current Main Projects 
- Drawing Program Case Study
- Music Player Program Case Study

---

# HTML with inline CSS Boilerplate Checklist and Template Creation

**Used with "Learning HTML through Website Creation" & "Main Project Creation"**
- Below are minimum expectations
- Full Expectations include some creativity using `HTML Summary.txt` Document

Minimum Checklist
- [x] White Space: all indents are auto-formatted by WYSIWYG or three-spaces (standard from W3 Consortium)
- [x] h1-h6 tags
- [x] Paragraph Tags
- [x] Sematic Body Tags (see index.html)

Checklist: adding basic inline HTML tags
- [x] Bolding: ```<strong></strong>``` (or ```<b></b>```)
- [x] Italics: ```<em></em>``` (or ```<i></i>```)
- [x] Superscript: ```<sup></sup>```
- [x] Subscript: ```<sub></sub>```

Checklist: adding HTML Hyperlinks
- [x] using anchors, minimum code ```<a href=""></a>```
- [x] using Browser Navigation Buttons by including or excluding *Open in a New Tab*, ```target="_blank"```
  - Remember, able to add other attributes and styles as needed and researched
- [x] adding whitespace where appropriate, HTML readable and not changing the Browser Rendering
- Commenting Source Webpage with URL, Actual URL and date accessed, with
  - [x] ```<blockquote cite="">```QUOTATION HERE, if used```</blockquote>```
  - [x] ```<!-- Date Accessed 20181011-->```, using International Numbering System for Dates (year, moth, day)
  - OPTION: ```<q></q>```, inline quotation tag, however, look this up since some blogs describe different browsers as rendering this differently
- Example Hyperlinks using Google Search's 'Unique to Self' Search Returns (ensures reader searches what author searched)
  - [x] Word Definition: linked to words or images
  - [x] Image Search
  - [x] Webpage Information, like Wikipedia
- Note: Hyperlink to Image should open only the server's image file, or downloaded image as alternate with correct path to Images Folder

Checklist: adding Image HTML Tags
- Types of Images to Include
- CAUTION: any large images must be resized and cropped with online free tools or Photoshop, etc.
- [x] Sized Image using width-height attributes (able to be overwritten by CSS)
- [x] Sized Image with Hyperlink, using Browser Navigation Buttons
- [x] Mapped Image with various Hyperlinks (and Easter Eggs), using Style-Width-Height Attribute (not overwritten by CSS)

Checklist for Lists, optional in this project
- [x] Include Ordered (numbered) and Unordered (dots) lists

---

# Atom HTML Boilerplate to Introductory CS Boilerplate in a Child Template File
- HTML Self Learning Notes and References
- Discuss WYSIWYG (Notepad, Notepad++, Visual Studio Basic, etc.)
- Discuss typing tags, then text data, then HTML, then inline CSS as needed
- Discuss White Space as necessary for rendering (sometimes rendering is stopped if White Space not formatted properly)

### W3 Schools Reference Webpages
- HTML Tags must be included: `<html>, <head>, <body>`
- See: https://www.w3schools.com/html/default.asp for full HTML Tutorials listing
- `<head>`, <a href="https://www.w3schools.com/html/html_head.asp">Click Here for W3 Schools Reference</a>
- `<body>`, <a href="https://www.w3schools.com/html/html5_semantic_elements.asp">Click Here for W3 Schools Reference</a>
- Special Symbols, <a href="https://www.w3schools.com/html/html_symbols.asp">Click Here for W3 Schools Reference</a>

### Getting Started 
Type `html:5` to add boilerplate

### Beginning an HTML Doc
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
</html>
```

### Common Head Tags with inline CSS

```html
  <head>

    <!-- Used by keyboard -->
    <meta charset="utf-8">

    <title>Learning HTML</title>

    <!-- Used by Browser or Google Search-->
    <meta name="author" content="Mark Mercer">
    <meta name="description" content="Learning HTML by building a simple Website">
    <meta name="keywords" content="boilerplate, starter code, HTML, learning">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- viewport is meant for Responsive Web Design, which we will look at later -->
  </head>
```

### Common Semantic Body Tags

``` html
<body>
  <header><h1>Header Title</h1></header>
    <nav><h1>Navigation</h1></nav>
    <aside><p>This is the aside space.</p></aside>
    <section>
      <h3>Section 1</h3>
      <article>
        <p>This is article 1 in section 1.</p>
      </article>
      <article>
        <p>This is article 2 in section 1.</p>
      </article>
    </section>
    <section>
      <h3>Section 2</h3>
      <article>
        <p>This is article 1 in section 2.</p>
      </article>
      <article>
        <p>This is article 2 in section 2.</p>
      </article>
    </section>
</body>
```

### An Example Footer, including
- HTML Tags
- Blockquote with single line comment for date accessed
- Text Hyperlink with forced navigation experience (opening a new tab)
  - Also viewing other choices ATOM.io offers with autocomplete
- Example Special Symbol

``` html
<footer>
  <blockquote cite="https://www.brainyquote.com/quotes/mitch_kapor_163583">
    <!-- Date Accessed 20201120-->
  </blockquote>
  <p>
    <strong>"Getting information off the Internet is like taking a drink from a firehose."</strong>
    <em><a href="https://www.brainyquote.com/quotes/mitch_kapor_163583" target="_blank">
       - Mitch Kapor</a>
    </em>
  </p>
  <p>&copy Mark Mercer, powered by MercersKitchen in GitHub</p>

</footer>
```

### Additional HEAD Notes

General List of all HTML `<head>`
- `<title>`: title in tab, when added to favorites, displays title in search engine when website is hosted live (i.e. GitHub Hosting)
- `<meta>`: see notes and meta attributes below
- `<base>`: for all URLs not defined, this becomes the base URL, for example using Google Drive as a Folder
- Other tags studied in Intermediate Website Projects
  - link: use to link external style sheets
  - script: used to define JavaScript, client-side, scripts
  - style: General CSS Style name:values for this webpage

Metadata Notes
- General W3 Schools Reference, <a href="https://www.w3schools.com/tags/tag_meta.asp">Click Here</a>
- Always passed as name-value pairs
- Never displayed in Browser
- Cross-scripting can happen or JavaScript can access these through DOM Values: <a href="https://www.w3schools.com/jsref/dom_obj_meta.asp">Click Here for W3 Reference</a>
- <a href="">Click Here for enrichment examples of JavaScript or Cross Scripting Examples</a>

List of all meta attributes
- name="author | description | keywords | viewport" content="": <a href="https://www.w3schools.com/tags/att_meta_name.asp">Click Here for examples from W3 Schools</a>
- http-equiv="content-type | default-style | refresh" content="": <a href="https://www.w3schools.com/tags/att_meta_http_equiv.asp">Click Here for examples from W3 Schools</a>
- See HEAD Examples in <a href="https://github.com/QEHS-Websites/Intro-Who-Am-I-Project/tree/master/Pathway%20and%20Files#additional-boilerplate-for-who-am-i--essay-projects-both-introductory-projects">this boilerplate</a>

An Exemplar `<head>` with `<meta>` tags
```html
<meta charset="utf-8">

<title>Who Am I Project</title>

<meta name="author" content="Jane Doe">
<meta name="description" content="Example boilerplate for Who am I Project">
<meta name="keywords" content="boilerplate, starter code">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

### Additional Body Notes and Reference
- See <a href="https://github.com/MercersKitchen/Webpages-Sites/blob/master/HTML%20Lessons/HTML_Summary.txt">full HTML Reference<>
- See: https://github.com/MercersKitchen/Webpages-Sites/tree/master/HTML%20Lessons

#### HTML Layout Elements
https://www.w3schools.com/html/html_layout.asp

```html
<!-- Review specific tags such as h1-h6, p, & special symbols like &copy-->
<header><h1>Header Title</h1></header>
    <nav><h1>Navigation</h1></nav>
    <aside><p>This is the aside space.</p></aside>
    <section>
      <h3>Section 1</h3>
      <article>
        <p>This is article 1 in section 1.</p>
      </article>
      <article>
        <p>This is article 2 in section 1.</p>
      </article>
    </section>
    <section>
      <h3>Section 2</h3>
      <article>
        <p>This is article 1 in section 2.</p>
      </article>
      <article>
        <p>This is article 2 in section 2.</p>
      </article>
    </section>

  </body>

  <footer>&copy Mark Mercer, powered by MercersKitchen (GitHub)</footer>
```

---

# Text Resizing according to Responsive Design

---

Explore layout options in W3 Schools: https://www.w3schools.com/html/html_layout.asp
- Must use Responsive: https://www.w3schools.com/html/html_responsive.asp
  - Also see the W3 Schools Tutorial: https://www.w3schools.com/css/css_rwd_intro.asp
- Must use the box-sizing property to border-box (padding and border are inside total with and height of all elements)
  - images are easier to adjust
  - text is a little more difficult to vw units

---

Resizing Text
- Example: 
```html
<h1 style="font-size:10vw">Hello World</h1>
```

- Another example using Hello World Text or the Website for H-tags and P-Tags
```html
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>

<h1 style="font-size:10vw;">Responsive Text</h1>

<p style="font-size:5vw;">Resize the browser window to see how the text size scales.</p>

<p style="font-size:5vw;">Use the "vw" unit when sizing the text. 10vw will set the size to 10% of the viewport width.</p>

<p>Viewport is the browser window size. 1vw = 1% of viewport width. If the viewport is 50cm wide, 1vw is 0.5cm.</p>

</body>
</html>
```

---

# Image Resizing according to Responsive Design

---

Explore layout options in W3 Schools: https://www.w3schools.com/html/html_layout.asp
- Must use Responsive: https://www.w3schools.com/html/html_responsive.asp
  - Also see the W3 Schools Tutorial: https://www.w3schools.com/css/css_rwd_intro.asp
- Must use the box-sizing property to border-box (padding and border are inside total with and height of all elements)
  - images are easier to adjust
  - text is a little more difficult to vw units

---

Online image tools
- https://imageresizer.com/

- use inline width property set at 100%
- if trying to fit image into column, use max-width percentage, not window size
- height becomes automatic
```html
<img src="img_girl.jpg" style="width:100%;">

```
- if max-width is set to 100%, image will scale down but never up and be larger than original size
- Therefore, will have weird white space in rendering
```html
<img src="img_girl.jpg" style="max-width:100%;height:auto;">

```

- Advanced, Showing different images depending on media queries
- Illustrates picture and img together
- See https://www.w3schools.com/tags/tag_picture.asp
```html
<picture>
  <source srcset="img_smallflower.jpg" media="(max-width: 600px)">
  <source srcset="img_flowers.jpg" media="(max-width: 1500px)">
  <source srcset="flowers.jpg">
  <img src="img_smallflower.jpg" alt="Flowers">
</picture>

```

---

# Enrichment: Responsive Design ideas for Imbedding Videos

Imbedding Videos: https://www.w3schools.com/css/css_rwd_videos.asp


---

# Enrichment: Responsive Design ideas and full tutorial

Also see full Responsive Web Design Tutorial
- https://www.w3schools.com/css/css_rwd_intro.asp

Simple Two Column Example:
- See: https://www.w3schools.com/css/tryit.asp?filename=tryresponsive_webpage
- Or See: Responsive 2-Column Example Folder

Simple Three Column Examples
- See Responsive 3-Column Example Folder

Typical 12-Column Example, is getting a little too much for introductory CS, especially with small screens
- See https://www.w3schools.com/css/tryit.asp?filename=tryresponsive_cols

```html
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}

.header {
  border: 1px solid red;
  padding: 15px;
}

.row::after {
  content: "";
  clear: both;
  display: table;
}

[class*="col-"] {
  float: left;
  padding: 15px;
  border: 1px solid red;
}

.col-1 {width: 8.33%;}
.col-2 {width: 16.66%;}
.col-3 {width: 25%;}
.col-4 {width: 33.33%;}
.col-5 {width: 41.66%;}
.col-6 {width: 50%;}
.col-7 {width: 58.33%;}
.col-8 {width: 66.66%;}
.col-9 {width: 75%;}
.col-10 {width: 83.33%;}
.col-11 {width: 91.66%;}
.col-12 {width: 100%;}
</style>
</head>
<body>

<div class="header">
  <h1>Chania</h1>
</div>

<div class="row">

<div class="col-3">
  <ul>
    <li>The Flight</li>
    <li>The City</li>
    <li>The Island</li>
    <li>The Food</li>
  </ul>
</div>

<div class="col-9">
  <h1>The City</h1>
  <p>Chania is the capital of the Chania region on the island of Crete. The city can be divided in two parts, the old town and the modern city.</p>
  <p>Resize the browser window to see how the content respond to the resizing.</p>
</div>

</div>

</body>
</html>

```

- Media Queries
- You can see the size of a chrome window in the top right corner for a moment, resize, then toggle between the two screens to get the minimum media width you want before stacking

- Example 1
```html
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing:border-box;
}

.left {
  background-color:#2196F3;
  padding:20px;
  float:left;
  width:20%; /* The width is 20%, by default */
}

.main {
  background-color:#f1f1f1;
  padding:20px;
  float:left;
  width:60%; /* The width is 60%, by default */
}

.right {
  background-color:#4CAF50;
  padding:20px;
  float:left;
  width:20%; /* The width is 20%, by default */
}

/* Use a media query to add a break point at 800px: */
@media screen and (max-width:800px) {
  .left, .main, .right {
    width:100%; /* The width is 100%, when the viewport is 800px or smaller */
  }
}
</style>
</head>
<body>

<h2>Media Queries</h2>
<p>Resize the browser window.</p>

<p>Make sure you reach the breakpoint at 800px when resizing this frame.</p>

<div class="left">
  <p>Left Menu</p>
</div>

<div class="main">
  <p>Main Content</p>
</div>

<div class="right">
  <p>Right Content</p>
</div>

</body>
</html>
```

- Example 2
```html
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
}
.menu {
  float:left;
  width:20%;
  text-align:center;
}
.menu a {
  background-color:#e5e5e5;
  padding:8px;
  margin-top:7px;
  display:block;
  width:100%;
  color:black;
}
.main {
  float:left;
  width:60%;
  padding:0 20px;
}
.right {
  background-color:#e5e5e5;
  float:left;
  width:20%;
  padding:15px;
  margin-top:7px;
  text-align:center;
}

@media only screen and (max-width:620px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width:100%;
  }
}
</style>
</head>
<body style="font-family:Verdana;color:#aaaaaa;">

<div style="background-color:#e5e5e5;padding:15px;text-align:center;">
  <h1>Hello World</h1>
</div>

<div style="overflow:auto">
  <div class="menu">
    <a href="#">Link 1</a>
    <a href="#">Link 2</a>
    <a href="#">Link 3</a>
    <a href="#">Link 4</a>
  </div>

  <div class="main">
    <h2>Lorum Ipsum</h2>
    <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
  </div>

  <div class="right">
    <h2>About</h2>
    <p>Lorem ipsum dolor sit amet, consectetuer adipiscing elit.</p>
  </div>
</div>

<div style="background-color:#e5e5e5;text-align:center;padding:10px;margin-top:7px;">© copyright w3schools.com</div>

</body>
</html>

```

---

# Enrichment: Setting up the Chrome Browser for HTML & CSS Validation

- HTML Validation
  - In Workona, point a TAB to https://validator.w3.org/
      - Able to validate hosted and local documents
  - See HTML Markup Validation: https://validator.w3.org/#validate_by_upload
- CSS Validation
  - In Workona, point a TAB to https://jigsaw.w3.org/css-validator/validator.html.en
  - Able to validate hosted and local documents
  - See CSS Markup Validation: https://jigsaw.w3.org/css-validator/validator.html.en#validate_by_upload
- Accessibility Testing as a Chrome Developer Tool
  - Accessibility Validation: Chrome Web Store / Extensions / aXe by Deque Systems (Deque University)
  - In the Chrome Store, search for "aXe, Deque Systems" and add it to Chrome
  - In Chrome/Extensions Settings, allow aXe to access URLs
  - Able to find this in Developer Tools and the Analyze Button

Example Videos using Accessibility: https://youtu.be/OGwKOxh5hqQ?t=5m28s

---

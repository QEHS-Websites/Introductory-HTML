# Introductory-HTML
Introductory HTML with inline CSS

See https://github.com/QEHS-Websites/LearningHTML.github.io
- and see public-facing version: https://qehs-websites.github.io/LearningHTML.github.io/

**Purpose:** build simple webpages that are linked to each other, rendered in a browser, using HTML
- Full Listing of HTML Tags: https://www.w3schools.com/tags/default.asp

Table of Contents
- Introduction to the Internet and Web Documents (with small actives to illustrate), <a href="https://github.com/QEHS-Websites/Introductory-HTML#introduction-to-the-internet-and-web-documents-with-small-actives-to-illustrate">
Click Here</a>
- Introduction to HTML5 using GitHub Markdown and Annotating Project Notes, <a href="https://github.com/QEHS-Websites/Introductory-HTML#introduction-to-html5-using-github-markdown">
Click Here</a>
- Review Website Mentoring for Simple `Who Am I` Template (Elementary Aged Children)
  - See: https://github.com/MercersKitchen/Website-Mentoring
  - See Dev Outreach Files (Must be compiled locally): https://github.com/Dev-Outreach/Introduction-Static-HTML
  - Review Code to Enable JavaScript enabling in Browser (JavaScript is Intermediate CS but learning about default settings in Browser is Introductory CS)
  - Code should be part of Boilerplate
  - Code can also illustrate security issues for Browser automatically running JavaScript
- HTML with inline CSS Boilerplate Checklist and Template Creation, <a href="https://github.com/QEHS-Websites/Introductory-HTML#html-with-inline-css-boilerplate-checklist-and-template-creation">
Click Here</a>
- Starting with WYSIWIG Boilerplate, develop Boilerplate for childPages / Templage.html, <a href="https://github.com/QEHS-Websites/Introductory-HTML#atom-html-boilerplate-to-introductory-cs-boilerplate-in-a-child-template-file">
Click Here</a>
- Text Data Entry, see below
- Formatting text data with Semantic, H1-H6, & P-tags, with inline Responsive CSS
- Image Lesson and See Below

Additional Ideas
- Reference Repositories, <a href="https://github.com/QEHS-Websites/Template-Websites">Click Here</a>
  - Template Single Page Website: See File and Folder Structure with included `ReadMe` Files (`.md` illustrated for GitHub Markdown, `.txt` also possible)
  - Template Multipage Website: TBA
- Learning to Write a Website, by Writing a Simple Website
  - See Public Facing Exemplar: TBA (https://github.com/QEHS-Websites/LearningHTML.github.io)
  - Hosted at (for online Synchronous Learning, instead of Mr. Mercer hosting locally with classroom-based Lesson): https://qehs-websites.github.io/LearningHTML.github.io/
- Enrichment: <a href="https://github.com/QEHS-Websites/Introductory-HTML#enrichment-setting-up-the-chrome-browser-for-html--css-validation">
Setting up Validation for HTML and CSS in Chrome</a>

**JS Fiddle**: can be used to prototype all sections of a Webpage in a Chromebook

# Introduction to the Internet and Web Documents (with small actives to illustrate)

Introductions to a Browser - Specifically Google Chrome (and other exist)
1. "What else can a browser do?"
   - https://www.makeuseof.com/tag/use-browser-notepad/, accessed 20180905
   - A Browser can be a notepad tool, as long as the tab stays open
   - Type the following code into the URL Bar

   ```html
   data:text/html, <html contenteditable>
   ```

   - See: https://www.makeuseof.com/tag/use-browser-notepad/ for additional ideas on how to make a browser a Notepad

   - Uses built-in defaults for font, size, and other formatting rules
   - Google will spell check all the typing
   - If Chrome saves tabs (in settings, "Start where you left off"), or you use Workona, Tab will remain ready for notes but typing will disappear

2. Pathways inside a computer
   - Windows, Folders, and Pathways

3. Pathways outside a computer: URLs in name or number
   - Learning how to read URLs
   - Local Scripting: see example of Browser Notepad
   - Local Hosting: see example of World War II Essay on the Holocaust
   - Client-server hosting: see below

Exploring & Illustrating Internet and Web Docs Architecture
- Main Skill Goal: Using CMD through Windows to sending "Packets" or Internet Messages
- Main Concept Goal: diagram image of Internet Architecture (Google Draw, Paper and Pencil, other methods)
  1. One diagram for all vocabulary
  2. Internet Client-Server Requests through 2 stub networks (2x switches with single router)
- Main Vocabulary for Client-server relationships of Real (MAC) Addressing and Logical Addressing
  - workstations & NIC Cards (real MAC Address)
  - stub networks (defined by 1 workstation & switch or 1 workstation & router)
  - LANs defined by switch
  - WANs defined by router (edge router)
  - MANs defined by region or provider
  - Backbone of Internet defined by "in the wild" routers
- Main Vocabulary for Internet Services Requests ("all at once" (Netflix), packets (checked))
  - DNS
  - Pathways
  - Browser
  - EMail Server
  - Print Server
- Main Commands Examples for CMD
  - /? | ?
  - ping
  - nslookup cisco.com
    - Note: https://www.cloudns.net/blog/10-most-used-nslookup-commands/, accessed 20201110
  - traceroute | tracert [use IP Address]

Brief Introduction to Web Documents Design: hypertext (HTTP & HTTPS)
- Ports for HTTP & HTTPS for IP Sockets
- Security Protocol of HTTPS

Introductions to Raspberry Pi, "Going Headless", and IP Sockets
- IP Sockets (IP Address : Port Number) needed to specify packet direction

---

# Introduction to HTML5 using GitHub Markdown

**Note**: Can be done in any device

GitHub Markdown, with Additional HTML rendered in GitHub ReadMe.md files.
- Note, other programs use Markdown for formatting a variety of messages. Markdown is much easier to use if you are used to it or have a "Summary Sheet".
- "Opens a students world to a new type of formatting."
- "Project External Documentation"

Creating Single Page Applications (static or dynamic websites)
- Goal: host at least one through GitHub Website Hosting, further introduction to Google Analytics and Keywords to link to searches
- Using HTML & inline CSS
- "The front end of project promotion."

Modern Examples of Websites, not promotional or business-style, worth researching and learning how to code
- Chrome Extensions: HTML5 (often simple JavaScript), make browser do more
- PWA: Progressive Web Apps, websites that feel like native Android Apps
- Note: can deploy PWAs through Chrome Extension package (Google This)

---

# HTML with inline CSS Boilerplate Checklist and Template Creation

**Used with "Learning HTML through Website Creation" & "Main Project Creation"**
- Below are minimum expectations
- Full Expectations include some creativity using `HTML Summary.txt` Document

Minimum Checklist (see <a href="https://github.com/MercersKitchen/Webpages-Sites/blob/master/HTML%20Lessons/HTML_Summary.txt">for full checklist</a>)
- Note: [] White Space: all indents are autoformatted by WYSIWYG or three-spaces (standard from W3 Consortium)
- h1-h6 tags
- Paragraph to ```<article><p>```

Checklist: adding basic inline HTML tags, Click Here for <a href="">Summary</a>, or <a href="">full HTML examples</a>
- [] Bolding: ```<strong></strong>``` (or ```<b></b>```)
- [] Italics: ```<em></em>``` (or ```<i></i>```)
- [] Superscript: ```<sup></sup>```
- [] Subscript: ```<sub></sub>```

Checklist: adding HTML Hyperlinks, Click Here for <a href="">Summary</a>, or <a href="">full HTML examples</a>
- [] using anchors, minimum code ```<a href=""></a>```
- [] using Browser Navigation Buttons by including or excluding *Open in a New Tab*, ```target="_blank"```
  - Remember, able to add other attributes and styles as needed and researched
- [] adding whitespace where appropriate, HTML readable and not changing the Browser Rendering
- [] Commenting Source Webpage with URL, Actual URL and date accessed, with
  - [] ```<blockquote cite="">```QUOTATION HERE, if used```</blockquote>```
  - [] ```<!-- Date Accessed 20181011-->```, using International Numbering System for Dates (year, moth, day)
  - OPTION: ```<q></q>```, inline quotation tag, however, look this up since some blogs describe different browsers as rendering this differently
- Example Hyperlinks using Google Search's 'Unique to Self' Search Returns (ensures reader searches what author searched)
  - [] Word Definition: linked to words or images
  - [] Image Search
  - [] Webpage Information, like Wikipedia
- Note: Hyperlink to Image should open only the server's image file, or downloaded image as alternate with correct path to Images Folder

Checklist: adding Image HTML Tags (See Lessons on Building <a href="">Image HTML4 to HTML5 Tags</a>)
- Types of Images to Include
- CAUTION: any large images must be resized and cropped with online free tools or Photoshop, etc.
- [] Sized Image using width-height attributes (able to be overwritten by CSS)
- [] Sized Image with Hyperlink, using Browser Navigation Buttons
- [] Mapped Image with various Hyperlinks (and Easter Eggs), using Style-Width-Height Attribute (not overwritten by CSS)

Checklist for Lists, optional in this project, see <a href="">Summary</a>, or <a href="">full HTML examples</a>
- Include Ordered (numbered) and Unordered (dots) lists

---

# Atom HTML Boilerplate to Introductory CS Boilerplate in a Child Template File
- HTML Self Learning Notes and References
- Discuss WYSIWYG (Notepad, Notepad++, Visual Studio Basic, Atom.io, etc.)
- Discuss typing tags, then text data, then HTML, then inline CSS as needed
- Discuss White Space as necessary for rendering (sometimes rendering is stopped if White Space not formatted properly)

### W3 Schools Reference Webpages
- HTML Tags must be included: `<html>, <head>, <body>`
- See: https://www.w3schools.com/html/default.asp for full HTML Tutorials listing
- `<head>`, <a href="https://www.w3schools.com/html/html_head.asp">Click Here for W3 Schools Reference</a>
- `<body>`, <a href="https://www.w3schools.com/html/html5_semantic_elements.asp">Click Here for W3 Schools Reference</a>
- Special Symbols, <a href="https://www.w3schools.com/html/html_symbols.asp">Click Here for W3 Schools Reference</a>

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

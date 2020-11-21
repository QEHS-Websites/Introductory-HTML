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

### Enrichment Topics
Google Image Search, "HTML Semantic Tags", <a href="https://www.google.com/search?q=HTML+Semantic+Tags&safe=strict&rlz=1C1GCEU_en&tbm=isch&source=iu&ictx=1&fir=nFVcRKSgo_LGQM%252C-s9bmbuSdmptrM%252C%252Fm%252F080fdhf&vet=1&usg=AI4_-kRvQn7QZPzDHTuv5Gl1zvD8lFzIJA&sa=X&ved=2ahUKEwiwqJ3vzZHtAhXJvJ4KHVUuAyoQ_B16BAgTEAM#imgrc=nFVcRKSgo_LGQM">
Example from 20201120</a>

Explore layout options in W3 Schools: https://www.w3schools.com/html/html_layout.asp

See Flexbox Option: https://www.w3schools.com/css/css3_flexbox.asp
- Matches most closely with multiple devices and ease into CSS

---

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
<!-- Content give value for name or http-equiv attribute, text entry in string or array string -->

<!-- meta http-equiv="default-style" content=""--> <!-- content matches css link exactly-->

<!-- Other meta attributes to be aware of -->

<!-- meta http-equiv="refresh" content="30"-->
<!-- Content forces a Internet Request to refresh webpage every "time value in seconds" -->
<!-- Use this when refreshes are needed -->

<!-- meta http-equiv="content-type" content="text/html; charset=UTF-8" -->
<!-- Already specified in the charset above-->
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

### Notes and Reference

**See HTML Lessons Website**: for illustration of HTML Tags
- Also includes inline CSS

---

**Note:** Students must create another GitHub Lesson's Repository
- Information here will be used for Assessment-style Hackathons
- Chosen Readings are Grade 10 Reading Level Equivalent from the English Department

Ideas to Explore Here, DOCs to Create
  - Compare
    - Bolding: ```<strong></strong>``` (or ```<b></b>```)
    - Italics: ```<em></em>``` (or ```<i></i>```)
    - Superscript: ```<sup></sup>```
    - Subscript: ```<sub></sub>```
  - Find default settings in Chrome ("where are these located"), change these if necessary
- Simple DIV Layout and HEAD-Section CSS Attribute Definitions
  - elated to HTML Tags and how to see those, for example <article>

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

# To Include:

Creating Splash Page and linking to different childPages with a tags and `href=""` with options
- Creating Organized and unorganized lists (i.e. on Splash Page as summary)
- Another Page (see exemplar): Comparing Heading and Paragraph TagsH1 - H7, combining with Semantic Tags
- Another Page (see exemplar): Sub and Super Script Tags
- Another Page, formatting example (see exemplar): Delete this DIVs, HTML_BoilerplateDIV_v1, HTML_BoilerplateDIV_v2
- Image Lessons
  - See example: Image.html
  - See Image Lessons in childPages Exemplars
  - See Images Folder for other examples
- See HTML Summary, what has not been made into example pages, what needs to be

Note: rewrite current website to learn about webpages

Note: Review Chrome's inspection elements to learn about how a webpage is laid out

---

# To Include:

META Data - Prepares the body for searching and rendering in browser
- Google Search to see use of UTF-8
- Other Meta Data used in HEAD
- Web Browsers: https://en.wikipedia.org/wiki/Web_browser
- Browsers need to read what language is declared first
- Different browser versions will run different versions of languages differently
- QE Runs the latest versions of all
- Other countries do not - web developers must test website versions on a variety of monitor sizes, browsers, language versions

HTML Semantic Tags & Boiler Plate: Footer
- Quote with Hyperlink opening new Tab
- Blockquote URL Reference with Date Accessed


---

# To Include:

HTML Semantic Tags & Boiler Plate: Body
- Note: auto formatting tags (preset in browser, user controlled)
- **Learn Pieces of HTML Sematic Tags and boilerplate while learning auto formatting**
- Learn File Navigation in index.html with hyperlinks to childPages
- Visualize HTML Layout with DIVs
- Auto Formatting Example Pages
  - Headings vs. Paragraph DOC (includes <br>)
    - H1 - H7, p
    - Includes <br>
  - Ordered and Unordered Lists (simple formatting & more HTML Options)
  - TBA

Review all pages and visualize where the HTML Sections are using DIVs and inline CSS

#### Ideas
Where does inline CSS get added in this list

Redo Previous auto formatted DOCs with inline CSS (inline rewrites HTML)
Note: CSS Section and File Overwrite Options

- Paragraph formatting: copy and past for Essay Project
- Essay's are the most difficult to read ... probably taught the most in all subjects
- Using hyperlinks in paragraphs: a-tag with href attribute

- Simple Ordered and Unordered List Page
- Using More attributes page

- Hyperlinks & Images-Intro
- img-tag and src attribute
- img-tag with altattributre (visually imparted and website code, semantic, is read to person to "see" website)
- Advanced Images

- Introductory Example for Essay Planning, Example #2

- Intermediate Business Page Website, after CSS Lessons, Developing a Splash Page: See Example 1

- Construct Essay Project
- Refer to HTML Summary
- Create Interactive Essay Project

---

# To Include

Concepts

Image Expectations:
Creating Image Tags
- File downloaded and optimized for cropping and memory size using online tools
- URL blockquote-cited with date accessed
- File commented with original dimensions
- <img> width and height attributes scaled for aspect ratio
- Any mapped images have style width and height inside img tag

Current Ideas
- Creating a Repository: new repository
- Creating Pathways and Files:
- index.html, Images, Videos, Media
- Simple Text and Hyperlinks: quote in Footer
- Adding External Hyperlinks, using Browser TAB navigation

Lessons Descriptions to Include
- Text copy lessons, into HTML Layout
  - Create completed Essay Project, text copy DOC, with hint (make more sections and articles than HTML Layout)
- Hyperlink Lessons
- Image Lessons

Create DOC to see H1 - H6 progression and paragraph progression
- compare to DIV and br (automatic formatting using browser's presets)

Add CSS Borders to "see" HTML Divisions in rendered page's HTML Layout

Use boarder around image divs
- Moving DIVs with CSS (Intermediate)

See example about JavaScript opening all links in external tabs

See example about JavaScript button showing more information

Add Code Academy Resources
- HTML, CSS
- JavaScript
- Build a Website, Build an Interactive Website

Also check out Khan Academy

---

# To Include: Flexbox ideas

See https://www.w3schools.com/css/css3_flexbox.asp
- best introductory head and inline CSS after DIV finished

---

# Introductory-HTML
Introductory HTML with inline CSS

Table of Contents
- Introduction to the Internet and Web Documents (with small actives to illustrate), <a href="">Click Here when URL Added</a>
- Introduction to HTML5 using GitHub Markdown and Annotating Project Notes, <a href="">Click Here when URL Added</a>

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

# To Include: HTML Self Learning Notes and References

HTML Lessons for the following HTML Features
   - HTML Tags must be included: `<html>, <head>, <body>`
   - `<head>`, <a href="https://www.w3schools.com/html/html_head.asp">Click Here for W3 Schools Reference</a>
   - `<body>`
     - <a href="https://github.com/MercersKitchen/CS10#html-layout-elements">Click Here for HTML Layout Notes in this document</a>

## HEAD Notes

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

## Body Notes and Reference
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

# To Include: Setting up the Chrome Browser for HTML & CSS Validation

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


---

# To Include:


---

# To Include:


---

# To Include:


---

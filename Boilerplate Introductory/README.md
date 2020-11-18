# Introductory Boilerplate
Creating Boilerplate

Steps
- Create a new text document: Right Click / New / Text Document
- Rename DOC and File Extension: index.html
- Add Automatic Boilerplate by typing html in blank .html file

Automatic HTML Boilerplate from Atom
```html
<!DOCTYPE html>
<html lang="en" dir="ltr">
  <head>
    <meta charset="utf-8">
    <title></title>
  </head>
  <body>

  </body>
</html>
```

- Add the following tags, layout, footer elements and special symbols

```html
<!DOCTYPE html>

<html lang="en" dir="ltr">

  <head>
    <meta charset="utf-8">

    <title>TAB Title</title>

    <meta name="author" content="Mark Mercer">
    <meta name="description" content=""> <!-- Webpage Description -->
    <meta name="keywords" content=""> <!-- Key Words for conducting searches in Search Engines -->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- Content gives value for name or http-equiv attribute, text entry for typeof string or array string -->

  </head>

  <body>

    <header><h1>Header Title</h1></header>
    <nav><h2>Navigation Menu</h2></nav>
    <aside><p>The Aside Space</p></aside>
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

  <footer>
    <p>&copy Mark Mercer, powered by MercersKitchen in GitHub</p>
  </footer>

</html>
```

## Additional Footer Information, a quote demonstrating how to reference others' work through URLs

```html
<!-- Date Accessed: 20180915 -->
<blockquote cite="https://www.brainyquote.com/quotes/mitchell_kapor_163583">
  <p>
    <em>Getting information off the Internet is like taking a drink from a firehose.<em>
  </p>
  <p>
    <strong>
      <a href="https://www.brainyquote.com/quotes/mitchell_kapor_163583" target="_blank">
        Mitchell Kapor
      <a/>
    <strong>
  </p>
  <br>
</blockquote>
```

---

## Extra Meta Data Notes: mostly redundant
- content matches css link exactly

```html
<meta http-equiv="default-style" content=""-->
```

- Use when page refreshes are needed, like a business webpage (currently CS20)

```html
<meta http-equiv="refresh" content="30"> <!-- Content forces a Internet Request to refresh webpage every "time value in seconds" -->
```

- Redundant given boilerplate above

```html
<meta http-equiv="content-type" content="text/html; charset=UTF-8">
```

---

# Ideas to Include

DIV

NoScript

---

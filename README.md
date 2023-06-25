# c23

Úvod do webových technologií.

## Obsah

<details>
<summary>TL;DR</summary>
- HTML definuje strukturu stránky.
- CSS definuje zobrazení stránky.
- JavaScript přidává funkcionalitu navíc.
- HTTP je protokol pomocí kterého kominikujeme mezi klientem a serverem.
- JSON je formát/zápis pro ukládání dat.
</details>

<details><summary>HTML (Hypertext Markup Language)</summary>

- HTML
  - Struktura stránky (Document outline)
    - `<!DOCTYPE>`
    - `<html>`&hellip;`</html>`
    - `<head>`&hellip;`</head>` (Page information)
      - `<base />`
      - [x] `<meta />` meta informace
      - [x] `<meta charset="UTF-8 />` kódování stránky
      - [x] `<title />` titulek stránky
    - `<body>`&hellip;`</body>`
  - Komentáře `<!-- oneline or multiline comment -->`
  - Struktura a obsah (page content and structure)
  - Obsah (Page content
    - [x] `<h1>`... `<h6>` Heading
    - `<span>` Inline section
    - [x] `<p>` Paragraph
    - [x] `<br />` Zalomení (Line break): používej jen málo
    - [ ] `&nbsp;` Nezalomitelná mezera
    - [x] `<hr />` Horizontal rule (line)
  - [x] Links
    - Page link
    - Email link: `<a href="mailto:m.bluth@example.com">Email</a>`
    - `<a name="anchor"`> Anchor
    - `<a href="#anchor">` Link to anchor (works for any element id)
  - Text markups
    - `<i>`
    - `<b>`
    - &hellip;
  - Lists
    - [x] `<ul>` Unordered list
    - [x] `<ol>` Ordered list
    - [x] `<dl>` Definition list
  - Tables: `<table>`
  - Forms and Inputs: `<form>`, `<input>`, `<textarea>`
  - Media and embeding
    - Image: `<img>`
    - Video: `<video>
    - Audio: `<audio>`
    - Frame: `<iframe>`
  - Canvas: `<canvas>`
    - 2D context
    - WebGL context
  - Členění stránky
    - [x] `<div>` Page division (division)
    - `<aside>` Sidebar
    - `<nav>` Navigation
    - `<header>` Header
    - `<footer>` Footer
    - `<main>` Main
    - `<article>` Article
    - `<section>`

HTML elements; HTML attributes

- Syntax a sémantika HTML elementů.
- HTML uvedem pomocí `<!DOCTYPE html>`.
- HTML je  *case insensitive* tzn., že `doctype` je to samé jako `DOCTYPE` nebo `Doctype`, nicméně je dobré zapisovat jako `DOCTYPE`.
- HTML sekce `<head>` slouží pro metada a není určena k zobrazení.
- HTML sekce `<body>` slouží pro zobrazení obsahu

`<h1>` je hlavní nadpis stránky a měl by být uveden pouze jednou.

- CTRL + Shift + I zapíná v Chrome vývojářské nástroje.
- CTRL + + zvětšuje font
- CTRL + - zmenšuje font
- CTRL + 0 resetuje na 100%

- Element, atribut tag
 - HTML element je reprezentován HTML tagem.
 - HTML tag může být párový nebo nepárový.
- Element
 1. blokový (většina)
 2. řádkový

Řadkový se dá zobrazit jako blokový a naopak, pomocí CSS.

Tag může mít atribut Elemnt může vlastnost.

```
<!-- párový -->
<h1> ... </h1>

<!-- nepárový -->
<img />
```

- Úprava textu a typografie

`<b>` vs `<strong>`

`<i>` vs `<em>`
</details>

<details><summary>CSS (Cascading Style Sheets)</summary>

 - `<link>`
 - `@import`
 - `#` id
 - `.` class
 
</details>

<details><summary>JavaScript: DOM, JSON, HTTP, CORS </summary>

- DOM
- JS: Objects
- JS: Functions
- JS: Prototypes
- JSON
</details>

<details><summary>HTTP (Hypertext Transfer Protocol)</summary>
</details>

 ## Resources
 
- [Chrome Development Tools](https://developer.chrome.com/docs/devtools/) 
- [Firefox Development Tools](https://firefox-source-docs.mozilla.org/devtools-user/)

- Mozilla HTML https://developer.mozilla.org/en-US/docs/Web/HTML
- Mozilla CSS https://developer.mozilla.org/en-US/docs/Web/CSS
- https://www.jakpsatweb.cz/
- https://www.quora.com/What-are-some-tips-for-a-person-learning-HTML?no_redirect=1
- https://en.wikipedia.org/wiki/CSS
- https://www.json.org/json-en.html
- https://developer.chrome.com/articles/css-nesting/

- https://kyoshee.medium.com/building-tabs-component-using-only-html-and-css-no-js-74db7790fad2
  - https://codepen.io/kyoshee/pen/NWyvjjN

## Notes

```shell
git subtree push --prefix=dist origin gh-pages
```

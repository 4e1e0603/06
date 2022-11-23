# course-webtech

Úvod do webových technologií: HTML, CSS, JavaScript, HTTP, JSON

## TL;DR

- HTML definuje strukturu stránky.
- CSS definuje vzhled prvků stránky.
- JavaScript přidává funkcionalitu navíc.
- HTTP je protokol pomocí kterého kominikujeme mezi klientem a serverem.
- JSON je formát/zápis pro ukládání dat.

## HTML 5

- Document outline
  - `<!DOCTYPE>`
  - `<html>`
  - `<head>`
  - `<body>`
- Comments
  - `<!-- comment -->`  (VS Code umí *comment/uncoment*.)
- Page information
  - `<base />`
  - [x] `<meta />`
    - [x] `<meta charset="UTF-8 />` Důležitý
  - [x] `<title />`
- Page structure
  - [x] `<h1>`... `<h6>` Heading
  - [x] `<div>` Page section (division)
  - `<span>` Inline section
  - [x] `<p>` Paragraph
  - [x] `<br />` Line break: používej jen málo
  - [x] `<hr />` Horizontal rule (line)
  - `<aside>` Sidebar
  - `<nav>` Navigation
  - `<header>` Header
  - `<footer>` Footer
  - `<main>` Main
  - `<article>` Article
  - `<section>`
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

 *italica*, **bold**

HTML elements; HTML attributes

- Syntax a sémantika HTML elementů.
- HTML uvedem pomocí `<!DOCTYPE html>`.
- HTML je  *case insensitive* tzn., že `doctype` je to samé jako `DOCTYPE` nebo `Doctype`, nicméně je dobré zapisovat jako `DOCTYPE`.
- HTML sekce `<head>` slouží pro metada a není určena k zobrazení.
- HTML sekce `<body>` slouží pro zobrazení obsahu

`<h1>` je hlavní nadpis stránky a měl by být uveden pouze jednou.

- CTRL + Shif + I zapíná v Chrome vývojářské nástroje.
- CTRL + + zvětšuje font
- CTRL + - zmenšuje font
- CTRL + 0 resetuje na 100%

## Element, atribut tag

HTML element je reprezentován HTML tagem.
HTML tag může být párový nebo nepárový.

Element
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

## Úprava textu

`<b>` vs `<strong>`

`<i>` vs `<em>`


 ## CSS

 - `<link>`
 - `@import`
 - `#` id
 - `.` class

 ## JavaScript: DOM, JSON, HTTP, CORS

 ### DOM

 ### JSON

 ### HTTP

 ### JS: Objects
 ### JS: Functions
 ### JS: Prototypes

 ## Resources

- Mozilla HTML https://developer.mozilla.org/en-US/docs/Web/HTML
- Mozilla CSS https://developer.mozilla.org/en-US/docs/Web/CSS
- https://www.jakpsatweb.cz/
- https://www.quora.com/What-are-some-tips-for-a-person-learning-HTML?no_redirect=1
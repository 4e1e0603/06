# course-webtech

Web technologies introduction: HTML, CSS, JS

## TL;DR

- HTML definuje strukturu stránky.
- CSS definuje vzhled prvků stránky.
- JavaScript přidává funkcionalitu navíc.

## HTML 5

HTML elements; HTML attributes

HTML je case insensitive
doctype je to samé jako DOCTYPE  jako Doctype

sekce Head slouží pro metadata (není zobrazena)
sekce Body slouží pro zobrazené obsahu

`<h1>` je hlavní nadpi stsránky a měl by být uveden pouze jednou (sémantika).

CTRL + Shif + I zapíná v Chrome vývojářské nástroje.
CTRL + + zvětšuje font
CTR + - zmenšuje font
CTRL + 0 resetuje na 100%

## Element, atribut tag

HTML Element je reprezentován HTML tagem
HTML tag může být párový nebo nepárový


Rozeznáváme dva druhy prvků
1. blokový
2. řádkový

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
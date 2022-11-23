# HTML Docs
Simple definitions for HTML basic course

- [HTML: HyperText Markup Language](#html-hypertext-markup-language)
    * [Definition](#definition)
        + [What is Markup Language?](#what-is-markup-language)
- [Elements](#elements)
    * [Popular Elements](#popular-elements)
    * [All Elements](#all-elements)
- [HTML Basic Examples](#html-basic-examples)
    * [The <!DOCTYPE> Declaration](#the-doctype-declaration)
    * [HTML Headings](#html-headings)
    * [HTML Paragraphs](#html-paragraphs)
    * [HTML Links](#html-links)
- [HTML Elements](#html-elements)
    * [HTML Layout Elements and Techniques](#html-layout-elements-and-techniques)
    * [HTML Attributes](#html-attributes)
    * [HTML Styles](#html-styles)
    * [HTML JavaScript](#html-javascript)
    * [HTML - The Head Element](#html---the-head-element)


------------

## HTML: HyperText Markup Language

### Definition
HTML (HyperText Markup Language) is the most basic building block of the Web. It defines the meaning and structure of web content. Other technologies besides HTML are generally used to describe a web page's appearance/presentation (CSS) or functionality/behavior (JavaScript).
(via https://developer.mozilla.org/en-US/docs/Web/HTML)

"Hypertext" refers to links that connect web pages to one another, either within a single website or between websites. Links are a fundamental aspect of the Web. By uploading content to the Internet and linking it to pages created by other people, you become an active participant in the World Wide Web.


#### What is Markup Language?

Markup language refers to a text-encoding system consisting of a set of symbols inserted in a text document to control its structure, formatting, or the relationship between its parts.

A markup language is a set of rules governing what markup information may be included in a document and how it is combined with the content of the document in a way to facilitate use by humans and computer programs.
(via https://en.wikipedia.org/wiki/Markup_language)

## Elements

### Popular Elements

HTML uses "markup" to annotate text, images, and other content for display in a Web browser. HTML markup includes special "elements" such as 
`<head>, <title>, <body>, <header>, <footer>, <article>, <section>, <p>, <div>, <span>, <img>, <aside>, <audio>, <canvas>, <datalist>, <details>, <embed>, <nav>, <output>, <progress>, <video>, <ul>, <ol>, <li> and many others.`

### All Elements

You can reference to all Markups here:

https://developer.mozilla.org/en-US/docs/Web/HTML/Element

## HTML Elements

Check https://www.w3schools.com/html/html_elements.asp


### HTML - The Head Element

https://www.w3schools.com/html/html_head.asp

### HTML Layout Elements and Techniques

https://www.w3schools.com/html/html_layout.asp

![img_sem_elements](https://user-images.githubusercontent.com/56475977/203615611-811951f6-a534-46f7-834e-c7eeb80b21ce.gif)

## HTML Attributes

https://www.w3schools.com/html/html_attributes.asp

## HTML Styles

https://www.w3schools.com/html/html_styles.asp

## HTML JavaScript

https://www.w3schools.com/html/html_scripts.asp

## HTML - The Head Element

https://www.w3schools.com/html/html_head.asp

## HTML Basic Examples

via https://www.w3schools.com/html/html_basic.asp

```html
<!DOCTYPE html>
<html>
<body>

<h1>My First Heading</h1>
<p>My first paragraph.</p>

</body>
</html>
```

### The <!DOCTYPE> Declaration

The <!DOCTYPE> declaration represents the document type, and helps browsers to display web pages correctly.

It must only appear once, at the top of the page (before any HTML tags).

The <!DOCTYPE> declaration is not case sensitive.

The <!DOCTYPE> declaration for HTML5 is:

```html
<!DOCTYPE html>
```

### HTML Headings

HTML headings are defined with the `<h1>` to `<h6>` tags.

`<h1>` defines the most important heading. `<h6>` defines the least important heading: 
```html
<h1>This is heading 1</h1>
<h2>This is heading 2</h2>
<h3>This is heading 3</h3>
<h4>This is heading 4</h4>
<h5>This is heading 5</h5>
<h6>This is heading 6</h6>
```

### HTML Paragraphs

HTML paragraphs are defined with the `<p>` tag:

```html
<p>This is a paragraph.</p>
<p>This is another paragraph.</p>
```

### HTML Links
HTML links are defined with the `<a>` tag:
```html
<a href="https://www.w3schools.com">This is a link</a>
```

### HTML Images

HTML images are defined with the <img> tag.

The source file (src), alternative text (alt), width, and height are provided as attributes:
```html
<img src="w3schools.jpg" alt="W3Schools.com" width="104" height="142">
```


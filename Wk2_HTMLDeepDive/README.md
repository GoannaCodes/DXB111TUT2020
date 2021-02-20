# HTML Semantics
Important for styling, maintaining code, accessibility and for search engine optimisation.

## Frontmatter
Contains `metadata` which is data about data. This content belongs in the `<head>` tag so that it is not displayed on webpage and for browser/SE use

`<title>Your web page's title.</title>`
  - This can be seen in the browser tab, but
nowhere else. Typically used by search
engines.

`<html lang ="en">`
  - This tells the browser that the human
language this is written is English.

`<meta charset="utf-8">`
  - The character set. The symbols your
computer reads as a language.

## Header and Footer
`<header>` is the visible top of a webpage. Often contains a navigation `<nav>` 
  - should not be confused for `<head>` which is used for metadata

`<footer>` is the bottom of the webpage. Often used as secondary navigation or to attach external links to other media (i.e. socials)
  - should be universally used across all webpages

## Main content
`<main>` is a box that contains sections `<section>`, articles `<article>` and dividers `<div>`
  - should contain anything that constitutes as 'main' content of a page
    
`<article>` can contain parapgraphs `<p>`, headings `<h1>, <h2>,...`, images `<img>`, and lists `<ul>, <ol>`
  - should be used to encapsulate a blog post, recipe or magazine article
  
`<aside>` can contain secondary navigation, page links, or external resources
  - should be things that relate to article/site content, but aren't super important
  
`<section>` are used for content that deserves its own section or doesn't belong in an article or aside
  - mainly use parapgraphs `<p>`, headings `<h1>, <h2>,...`, images `<img>`

`<div>` is used if content does not belong inside a header, article, aside or section
  - also used to give more control over selectors by grouping elements
  
## Linking images
### Local image source
`<img src="/images/cat.jpg" alt="Cat picture">`
### Online image source
`<img src="https://www.w3schools.com/i
mages/w3schools_green.jpg" alt="W3Sch
ools.com">`

`src` is where the image source can be found (from the perspective of the HTML file)
`alt` is alternative text that is displayed when an image fails to load and can be used for accessibility and SEO purposes

## Specifying colours
### Web-safe Colour Names
`h2 {background-color:red;}`
### Hexadecimal Colours
`h2 {background-color: #ff0000;}`
###RGB Colours
`h2 {background-color:rgb(255, 0, 0);}`
### RGBA Colours
`h2 {background-color:rgba(255, 0, 0, 0.3);}`

#Third Lesson
## What do we need when we get a page design?
### Direction type: RTL
- **Header**:
 - Logo + navbar (background: #282828)
 - Main image:
  - text heading (white)
  - image, (background: #949381)
  -  botom black border (about 10px)(background: #282828)

- **Main**:
 - background: #e9e9e9
 - Heading (h3)(#444444), left side showing time per lecture (same color)
 - 1*6 thumbnails with short description of the lecturer:
  - background png with lecturer pic
  - below:
   - (white) box with a short desctiption (p) (15px border radius )
   - at the top of the box another "speach" box with the lecturer title (h3) + name (p) (background: #d0eae9).

---------------------------------------------------------------------------------------------------

## ALWAYS Think Ahead

We will devide our file system to a few files of CSS, HTML and JS

**Why?**

Because then, if we will need to modify our color pallet, we will change our *colors.css* file, instead the entire CSS file.

## Design to Markup
**What to look at first?**
- If i have a good components
- **Solid HTML** is the basis for every good website
- [Motherfuckingwebsite](http://motherfuckingwebsite.com/)

## Methodology
- Write everything on a paper (or note)
- the name should describe the role of each components
- breakdown the elements for each section
- hierarchy of components
- **Think In Patterns**: e.g break down the page to reusable components.

## HTML 5 Semantics
**What does it mean?**
A common language between the developers (*example: <div>*).
Also, google uses its algorithm to grade website by good semantics.

### Sectioning & Grouping Elements
**Sectioning**
- ```<nav></nav>``` -  represents a section of a page that links to other pages or to parts within the page: a section with navigation links.
- ```<article></article>``` -  represents a self-contained composition in a document, page, application, or site, which is intended to be independently distributable or reusable.
- ```<section></section>``` -  represents a generic section of a document, i.e., a thematic grouping of content, typically with a heading. Each ```<section>``` should be identified, typically by including a heading (```<h1>-<h6>``` element) as a child of the ```<section>``` element.
- ```<aside></aside>``` - represents a section of the page with content connected tangentially to the rest, which could be considered separate from that content.
- ```<figure>``` and ```<figcaption>``` - the *figcaption* is used to describe the *figure* element.

**Grouping**
- ```<main></main>```
- ```<header></header>```
- ```<footer></footer>```

### Attributes
Every Html tag have their own Attributes, a small section of tag have their own attributes (Ex. image has an attribute width and height).

## 2 types of elements:
1. **Block** - Uses the **Whole** line (e.g ```<div>```)
2. **Inline** - Uses only the the space that it needs to (not taking a whole line, e.g ```<span>```).

*Unclosed tags* - tags without a closing, will be inside the ```<head>``` tag and will show an informative content of the page, usually it will be a ```<meta>``` tag.

## Homework
1. Build the entire web_b03.png page
2. Get all the components descriptions from the MDN

## Extras
- [CSS Zen Gardens](http://www.csszengarden.com/)
- [HTML 5 Outliner](https://gsnedders.html5.org/outliner/)
- [HTML 5 Doctor](http://html5doctor.com/)
- [Emmet cheat-sheet](http://docs.emmet.io/cheat-sheet/)
- [D3jss - Data-Driven Documents with CSS & JS](http://d3js.org/)
- [Adobe Color Pallets](https://color.adobe.com/).

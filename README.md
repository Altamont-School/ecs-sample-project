# ecs-sample-project
Sample HTML project for Exploring Computer Science (ECS).

## The DOM
DOM stands for **Document Object Model.** Essentially, this is a webpage! A webpage is composed of different elements. An element can be anything from a header, to an image, to an item in a list. Broadly, the DOM has two components:
* Head
* Body

The head contains our page's title, references for our **style sheets,** and things like **scripts** that will help control the behavior of the webpage. The body contains our page's structure and elements.

## Languages
Modern webpages typically consist of three different languages:
* Hypertext Markup Language (HTML)
* Cascading Style Sheets (CSS)
* JavaScript (JS)

We'll spend the rest of the quarter talking about HTML and CSS. These two language are the bread and butter of web design. **HTML** creates the structure of a webpage -- these are the building blocks that allow for a page to be visible.

**CSS** provides the stylistic components of our page. Bottom line: without CSS, our websites would look terrible.

## HTML
HTML works by enclosing our code in something called a **tag.** For example, if we wanted to add a paragraph of text to a page, we would use the *paragraph* tag:

```HTML
<p>This is a paragraph of text.</p>
```

### Common HTML tags
**Heading** // A heading is used to introduce content.
```HTML
<h1>Biggest Heading</h1>
<h6>Smallest Heading</h6>
```

**Paragraph** // A paragraph is a block of text.
```HTML
<p>Like the example earlier.</p>
```

**Lists** // A "bulleted" list of items. `<ul>` stands for "unordered list" and `<li>` stands for "list item." The `<li>` series is **nested** inside of the `<ul>` **element.**
```HTML
<ul>
  <li>First item</li>
  <li>Second item</li>
  <li>Third item</li>
</ul>
```
**Anchor** // An anchor is a piece of text which marks the beginning and/or the end of a hypertext link.
```HTML
<a>Link to another page/site.</a>
```

**Button** // A button tag defines a clickable button. Lots of things can be turned into buttons, too.
```HTML
<button type="button">Click Me</button>
```
*NB: This is the first time we've seen something called an **attribute.** Attributes are ways of being more specific with our elements and giving them certain characteristics.*

**Image** // An anchor is a piece of text which marks the beginning and/or the end of a hypertext link.
```HTML
<img src="path/to/image/file" alt="Alternate text when hovering">
```
Images have an important attribute called `src`. This stands for **"source"** and is defined by a path to the file's image on the server (i.e., the source of the image).

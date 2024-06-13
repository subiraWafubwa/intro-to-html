# BREAKOUT ROOM 6 💪🏽

## What is HTML?

HTML, or HyperText Markup Language, is the standard language used to create and design web pages and web applications. It structures content on the web by using a variety of elements and tags that tell the browser how to display text, images, and other forms of multimedia onHTML, or HyperText Markup Language, is the standard language used to create and design web pages and web applications. It structures content on the web by using a variety of elements and tags that te a webpage.

## What are tags?

HTML tags are the building blocks of HTML, used to define and structure content on a web page. They are enclosed in angle brackets (< >) and typically come in pairs: an opening tag and a closing tag. The content between these tags is the element content. Some tags are self-closing.

### Some common html tags include

`<html>`: The root element that defines the entire HTML document.

`<head>`: Contains meta-information about the document (e.g., title, character set, styles, scripts).

`<title>`: Sets the title of the document, which appears in the browser's title bar or tab.

`<body>`: Contains the content of the HTML document, such as text, images, and links.

`<h1> to <h6>`: Header tags, with `<h1>` being the highest (or most important) level and `<h6>` the lowest.

`<p>`: Defines a paragraph.

## What are elements?

An element refers to a complete structure that typically consists of a start tag, content, and an end tag. Elements are the building blocks of HTML documents, defining the structure and content of web pages.

For example: This is a paragraph element.

> `<p>This is a paragraph.</p>`

And this is an image element which is self-closing

> `<img src="image.jpg" alt="An image description">`

## What are the differences between an element and a tag in HTML?

| Tags | Elements |
|----------|----------|
| Tags are the building blocks of HTML used to create elements. They are enclosed in angle brackets (< >) and typically come in pairs: an opening tag and a closing tag. | Elements consist of both the tags and the content they enclose. An element is a complete structure within an HTML document. |
| Tags define the start and end of an element, specifying the type of content and its purpose. Example: `<a>` defines the start of a hyperlink, and </a> defines its end. | Elements represent the actual content and structure of the web page, created by the tags. Example: `<a href="https://www.example.com">`Link`</a>` is an anchor element that creates a clickable link. |
| There are two main types of tags: opening tags (e.g., `<div>`) and closing tags (e.g., </div>). Some tags are self-closing (e.g., `<img />`). | Elements can be categorized as block-level or inline, but these categories apply to the entire element, not just the tags. Example: `<div>`...`</div>` (block-level element) and `<span>`...`</span>` (inline element). |
| Attributes are added to opening tags to provide additional information about the element. Attributes are not present in closing tags. Example: `<a href="https://www.example.com">` where href is an attribute. | Elements are modified or extended by attributes within their tags, influencing their behavior and display. Example: `<img src="image.jpg" alt="Description" width="300" height="200">` includes attributes that define the image's source, alter |

## Discuss the semantic elements and its benefits

Semantic elements in HTML are elements that convey meaning and structure to the content they enclose, both to the browser and to developers. They provide better accessibility, improved SEO, and clearer code structure. Unlike non-semantic elements (such as `<div>` and `<span>`), semantic elements describe their purpose and the type of content they contain. This makes the HTML document more readable and maintainable.

### Key Semantic Elements

`<header>`: Represents introductory content, typically a group of introductory or navigational aids.

> `<header>`
    > `<h1>` Page Title `</h1>`
> `</header>`

`<nav>`: Defines a set of navigation links.

> `<nav>`
    >    `<ul>`
        >   `<li><a href="#home">Home</a></li>`
        >   `<li><a href="#services">Services</a></li>`
        >   `<li><a href="#contact">Contact</a></li>`
    > `</ul>`
> `</nav>`

`<main>`: Represents the main content of the document. Only one `<main>` element should be used per document.

> `<main>`
    > `<h2>`Main Content`</h2>`
    > `<p>`This is the primary content of the page.`</p>`
> `</main>`

`<article>`: Represents a self-contained piece of content that could be distributed and reused independently.

> `<article>`
> `<h2>`Article Title`</h2>`
> `<p>`This is an article.`</p>`
> `</article>`

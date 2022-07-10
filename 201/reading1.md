# Reading 1

## Getting Started

### Notes

- TCP = Transmission Control Protocol
- DNS = Domain Name System
  - Like an address book for websites. When you type the URL it finds the IP of the website.

- When planning a website asks these questions
  1. What is the website about?
  2. What information are you presenting?
  3. What does your website look like?

    [source](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/What_will_your_website_look_like)

- Use the document object to access the html file

### Reading prompts

**Compose a short poem describing how HTTP sends data between computers.**

*A client sends requests*  
*The server says goodbye*  
*The data leaves the nest*

**Describe how HTML, CSS, and JS files are "parsed" in the browser.**

The browser loads the HTML first and that means the browser then sees the  `<script>` and the `<link>` tag. As it sees these it requests the JS/CSS files. It then applies the styles and compiles and executes the JavaScript.

**How can you find images to add to a website?**

Search for copyright free images.

**How do you create a `String` vs a `Number` in JavaScript?**

You create a string with quotations around the value and a number with nothing but a number  
`let stringExample = "This Is A String";`  
`let numberExample = 15;`

**What is a `Variable` and why are they important in JavaScript?**

A variable holds data, and it is important in any programming language to keep track of and potentially modify data.

## Intro to HTML

### Notes

- Anatomy of an HTML Element
![](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started/grumpy-cat-small.png) [source](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML/Getting_started)
- `<meta>` is a way to add metadata such as a description on the website or the character set the website uses

### Reading prompts

**What is an HTML attribute?**

An attribute is something inside the opening tag of an element that modifies it

**Describe the Anatomy of an HTMl element.**

An element consists of an opening tag, content after that tag but before the closing tag, and a closing tag to end it

**What is the Difference between <article> and <section> element tags?**

There is no difference technically, but it is easier to understand what's happening in the code if you use an article to surround articles and sections to surround sections

**What Elements does a “typical” website include?**

header, nav, main, sidebar, footer

**How does metadata influence Search Engine Optimization?**

Metadata communicates directly to the search engine and can highlight important information

**How is the <meta> HTML tag used when specifying metadata?**

It is self-closing and all metadata is defined as attributes inside the tag

## Misc

### Reading prompts

**What is the first step to designing a Website?**

Asking the questions noted in the first section of this page

**What is the most important question to answer when designing a Website?**

What do I want to accomplish?

**Why should you use an `<h1>` element over a `<span>` element to display a top level heading?**

h1 will automatically have styling to give the content the appearance of a header

**What are the benefits of using semantic tags in our HTML?**

SEO, screen readers can use it to help navigate, easier to read the code.

**Describe 2 things that require JavaScript in the Browser?**

Displaying dynamic content. Store input.

**How can you add JavaScript to an HTML document?**

Add a script tag with either a link to an external file or write the code as the content for the script element.

# 201 Course

## Class 01 Reading Notes

### Why do these topics matter?

These topics matter to me because they are the basic building blocks of coding. To become a good software engineer, one must understand all the basics.

### How  does HTTP sends data between computers?

First and foremost what is HTTP? HTTP is an application protocol that defines a language for clients and servers to speak to each other. Secondly this is how HTTP works:

- A  browser goes to a DNS server, and finds the real address of the server that the website lives on
- Then the browser sends an HTTP request message to the server, asking it to send a copy of the website to the client
- This message and all other data sent between the client and the server, is sent across your internet connection using TCP/IP
- If the server approves the client's request, the server sends the client a "200 OK" message, which means you can look at that website
- Then starts sending the website's files to the browser as a series of small chunks called data packets
- The browser assembles the small chunks into a complete web page and displays it to you

### How are HTML, CSS, and JS files “parsed” in the browser?

- The browser parses the HTML file first, and that leads to the browser recognizing any < link>-element references to external CSS stylesheets and any < script>-element references to scripts
- As the browser parses the HTML, it sends requests back to the server for any CSS files it has found from < link> elements, and any JavaScript files it has found from < script> elements, and from those, then parses the CSS and JavaScript
- The browser generates an in-memory DOM tree from the parsed HTML, generates an in-memory CSSOM structure from the parsed CSS, and compiles and executes the parsed JavaScript.
- As the browser builds the DOM tree and applies the styles from the CSSOM tree and executes the JavaScript, a visual representation of the page is painted to the screen, and the user sees the page content and can begin to interact with it.

### How can you find images to add to a Website?

They are many ways you can add an image to a website. One way is using a < img> element. This is an empty element that requires a minimum of one attribute to be useful, such as a src . The src attribute contains a path pointing to the image you want to embed in the page, which can be a relative or absolute URL. For example, if your image is called chicken.jpg, and it sits in the same directory as your HTML page, you could embed the image like so < img src="chicken.jpg">

### How do you create a String vs a Number in JavaScript?

- To create a string, just wrap any sequence of characters in quotes
- Number can be both integers and floating point, example: let a = 1;

### What is a Variable and why are they important in JavaScript?

**Variables** are containers for storing data. Here are some examples of JS variables:

- VAR: keyword is used in all JavaScript code from 1995 to 2015(must use for older browser)
- LET: If you think the value of the variable can change
- CONST: If you want a general rule: always declare variables with this one

**Variables** are important because you need to be careful on which one you use. You don't want to use a CONST if you think the variable can change.

### What is an HTML attribute?

HTML attributes provide additional information about HTML elements. All HTML elements can have attributes and usually come in name/value pairs like: name="value"

### What is the Anatomy of an HTMl element?

They are four main parts of an HTML element which follows:

- The opening tag: This consists of the name of the element
- The closing tag: This is the same as the opening tag, except that it includes a forward slash before the element name. This states where the element ends
- The content: This is the content of the element
- The element: The opening tag, the closing tag, and the content together comprise the element

**Example:** < p>this is the content</ p>

### What is the Difference between < article> and < section> element tags?

The difference between articles and section tags is, the < section> tag defines a section in a document. The < article> tag specifies independent, self-contained content.

### What Elements does a “typical” website include?

- header: < header>
- navigation bar: < nav>
- main content: < main>, with various content subsections represented by < article>, < section>, and < div> elements
- sidebar: < aside>; often placed inside < main>
- footer: < footer>

### How does metadata influence Search Engine Optimization?

Using metadata boosts your SEO efforts because it's written in the search engine's language. Which helps search engines better understand the topic of your webpages and content.

### How is the < meta> HTML tag used when specifying metadata?

A example of how < meta> could be used to specify metadata is placing this in your header: < meta charset="utf-8">

### What is the first step to designing a Website?

First step to designing a website is identify your goal. Here are some questions to ask yourself:

- What exactly do I want to accomplish?
- How will a website help me reach my goals?
- What needs to be done, and in what order, to reach my goals?

### What is the most important question to answer when designing a Website?

- What exactly do I want to accomplish?

### Why should you use an < h1> element over a < span> element to display a top level heading?

You should use a < H1> element over a < span> because a < span> has no semantic value, so it will not get any extra benefits.

### What are the benefits of using semantic tags in our HTML?

The semantic HTML tags help the search engines and other user devices to determine the importance and context of web pages. A page made with semantic elements are much easier to read and has greater accessibility. It also offers a better user experience.

### What 2 things that require JavaScript in the Browser?

- Storing useful values inside variables
- Adding interactive behavior to web pages

### How can you add JavaScript to an HTML document?

You can add JavaScript in an HTML document by using the dedicated HTML tag < script> that wraps around the JavaScript. The < script> tag can be placed in the < head> section of your HTML or in the < body> section, depending on when you want the JavaScript to load.

### Things I want to know more about:

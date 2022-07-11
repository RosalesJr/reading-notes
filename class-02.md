# Class 02 Reading notes

## Why do these topics matter?

The following topics matter because this is the foundation of coding. If you misuse any of these principles you run the risk having your code break on you. So practicing these fundamentals will save you time in the long run. Because you will be debugging less and coding more.

### Why is it important to use semantic elements in our HTML?

Having semantics elements in our HTML is bery important for many reasons. For example:

- Accessibility: Screen readers rely on semantics in HTML to process web pages and help users with low vision navigate them. Also Semantic tags tell screen reader users where they are and how they can interact with the current page
- Human Readability: Semantic markup allows developers to locate specific page elements faster
- SEO: semantic markup helps search engine crawlers navigate your page to better understand its structure and contents

### How many levels of headings are there in HTML?

In HTML six levels of heading are defined. They are:

- H1,H2,H3,H4,H5,H6

- H1 is the highest level and H6 is the lowest level.

### What are some uses for the < sup> and < sub> elements?

The **Sup** element has many uses some include:

- used to specify exponents

- comply with conventions or typographical standards

Side note: sup element is usually found in the body tag

**Sub** element is normally used for identifying characters that should be rendered in a subscript. It should be used to mark text not style.

### When using the < abbr> element, what attribute must be added to provide the full expansion of the term?

When using a **abbr** element you have to add a **title** attribute, to provide an expansion or definition.

### What are ways we can apply CSS to our HTML?

They are three ways to add CSS:

- **External CSS**- can change the look of an entire website by just changing one file, can be written in any text editor, and must be saved with a .css extension

- **Internal CSS**- may be used if one single HTML page has a unique style, is defined inside the < style > element, inside the head section

- **Inline CSS**- may be used to apply a unique style for a single element

### Why should we avoid using inline styles?

You should avoid to use inline style CSS because they don't separate content from design. Also it may clutter your code making it harder to read.

### Review the block of code below and answer the following questions

- **What is representing the selector?**
H2

- **Which components are the CSS declarations?**
color: black;
padding: 5px;
- **Which components are considered properties?**
Color and padding

### What data type is a sequence of text enclosed in single quote marks?

String is the data type that enclosese a sequence of text in single quote marks.

### List 4 types of JavaScript operators

- **Addition:** + symbol
- **Subtraction:** - symbol
- **Multiplication:** * symbol
- **Assignment:** = symbol
- **Does not equal:** !== symbol

### Describe a real world Problem you could solve with a Function

You can use a funtion to determine a population in a given area or to calculate your weekly salary.

### Making Decisions In Your Code – Conditionals

- An if statement checks a condtion and if it evaluates to true, then the code block will execute.

- What is the use of an else if:
You would use a **else if** when you want extra choices to your **if** and **else**. But each additional choice will require an additional block to be put in between.

- List 3 different types of comparison operators:

1. ===: strict equality
2. !==: strict-non-equality
3. <: less than
4. <=: less than or equal to
5. =>: greater than or equal to

- What is the difference between the logical operator && and ||?
- && — allows you to chain together expressions but all of them have to individually evaluate to be true for the whole expression to return true.
- | |  — allows you to chain together expressions but one or more of the expressions have to individually evaluate to be true for the whole expression to return true.

### Sources:

- [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)
- [How is CSS Structured](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/How_CSS_is_structured)
- [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics)
- [Making Decisions In Your Code](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/conditionals)

### Things I want to know more about
# Technical Writing Assignment

For guidance on setting up and submitting this assignment, refer to the Marcy lab School Docs How-To guide for [Working with Short Response and Coding Assignments](https://marcylabschool.gitbook.io/marcy-lab-school-docs/fullstack-curriculum/how-tos/working-with-assignments#how-to-work-on-assignments).

## Prompt 1

Do some research on semantic and non-semantic elements and share your findings. Your response should include:

- Examples of semantic and non-semantic tags
- The differences between semantic and non-semantic tags
- The benefits of using semantic tags (when possible)

### Response 1

- Ex. Semantic tags = <div></div>, <span></span>
- Ex. Non-semantic tags = <header></header>, <footer></footer>, <main></main>
  //
- The differences between a semantic and non-semantic tags is that semantic tags are more descriptive on which element of code is being written, while a non-semantic tag is a more general way to storing code. The way to make a non-semantic tag more specfic you will have to add on attributes like 'id', 'class', or 'name' to make the value name more unique.
  //
- The benefits of using a semantic tag, not only does it help with organizing code and makes it easier to read. But semantic tags defines the content in the code that's about to be written. Now it is faster and easier when making headers, footers, and adding in multiple tags to a web page.

## Prompt 2

Do some research on accessibility. What are some ways to make your website more accessible? Explain why it is important for developers to create websites that meet accessibility standards.

### Response 2

- Ways to make a website more accessible is by using Semantic HTML, adding an alternative image text, language attribute, hyperlinks and ARIA roles. An image alt text holds the purpose of adding more content like a description of the image, for whatever reason a user is not able to see the image they are still able to know what the image is. Also having well-structured HTML helps developers create code that is readable and organized. Using semantic HTML like <h1>, <p>, <header>, <main>, this descriptive tag helps to label code, and makes it easier for developers to keep track of their work. But when other users are reviewing the code it makes it easier for others to read. The Lang attribute is a helpful addition to every page on a website, because it helps to identify the primary language of browser, search engines, translations software and screen readers. For screen readers this attribute tells the text to speech how to pronounce the words. Descriptive hyperlinks help with accessibility because it explains to the user what the link they are about to click is about to take them to. Lastly to help with accessibility developers can use ARIA roles. These roles are a set of standards that allows interface controls to be more accessible to those who use assistive technologies. It's important for developers to meet accessibility standards because it allows accommodations to those who have disabilities or other limitations.

## Prompt 3

It is possible to add "inline" CSS styles to our html elements using the `style` attribute like so:

```html
<p style="color: red;">hello world</p>
```

While this is possible, it is a best practice to instead write styles in a separate CSS file. Provide at least one argument for why it _might_ be considered useful to write inline styles, and then provide a more compelling argument for writing styles in a separate CSS file.

### Response 3

- Writing styles in HTML using inline styling would be useful if you wanted to keep certin lines in a permenate style or if you would like to preview how different lines of code look in different styles.
  While these are helpful and useful steps to use, it better to style your work in a sperate css page.

## Prompt 4

Imagine you are teaching a brand new programmer a brief lesson about the `class` and `id` attributes in HTML as well as how to use them to style elements using CSS. Your lesson should have the following components:

- An explanation of the concept of "classes" and "ids" with an analogy.
- An example of the usage using an HTML code block and a CSS code block.
- An explanation of the syntax using the terms: **attribute**, **selector**

### Response 4

## Prompt 5

The Document Object Model (DOM) API provides functions for manipulating HTML documents. It is possible to build an entire website using only JavaScript and the DOM API, however is that the best practice?

When building a website, how can I decide which content I should write using HTML/CSS and which content I should create using the JavaScript and the DOM API?

### Response 5

//

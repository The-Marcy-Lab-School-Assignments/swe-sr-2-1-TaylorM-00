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
- The differences between semantic and non-semantic tags is that semantic tags are more descriptive on which element of code is being written, while a non-semantic tag is a more general way of storing code.
  The way to make a non-semantic tag more specific you will have to add on attributes like 'id', 'class', or 'name' to make the value name more unique.
  //
- The benefits of using a semantic tag, not only does it help with organizing code and makes it easier to read.
  But semantic tags define the content in the code that's about to be written.
  Now it is faster and easier when making headers, footers, and adding in multiple tags to a web page.

## Prompt 2

Do some research on accessibility. What are some ways to make your website more accessible? Explain why it is important for developers to create websites that meet accessibility standards.

### Response 2

Ways to make a website more accessible is by using Semantic HTML, adding an alternative image text, language attribute, hyperlinks and ARIA roles.
An image alt text holds the purpose of adding more content like a description of the image, for whatever reason a user is not able to see the image they are still able to know what the image is.
Also having well-structured HTML helps developers create code that is readable and organized. Using semantic HTML like <h1>, <p>, <header>, <main>, this descriptive tag helps to label code, and makes it easier for developers to keep track of their work.
But when other users are reviewing the code it makes it easier for others to read.
The Lang attribute is a helpful addition to every page on a website, because it helps to identify the primary language of browser, search engines, translations software and screen readers. For screen readers this attribute tells the text to speech how to pronounce the words.
Descriptive hyperlinks help with accessibility because it explains to the user what the link they are about to click is about to take them to.
Lastly to help with accessibility developers can use ARIA roles.
These roles are a set of standards that allows interface controls to be more accessible to those who use assistive technologies.
It's important for developers to meet accessibility standards because it allows accommodations to those who have disabilities or other limitations.

## Prompt 3

It is possible to add "inline" CSS styles to our html elements using the `style` attribute like so:

```html
<p style="color: red;">hello world</p>
```

While this is possible, it is a best practice to instead write styles in a separate CSS file. Provide at least one argument for why it _might_ be considered useful to write inline styles, and then provide a more compelling argument for writing styles in a separate CSS file.

### Response 3

Writing styles in HTML using inline styling would be useful if you wanted to keep certain lines in a permanent style or if you would like to preview how different lines of code look in different styles.
While these are helpful and useful steps to use, it is better to style your work in a separate css page.
To start, having a separate page for css will allow you to have all of your website graphics stored in its own file which will also make it easily accessible.
This makes it easier whenever changes have to be made because you won't have to go through HTML code to find what you're looking for.
Depending on internet connection and the size of the HTML file, using a css file will help you retrieve your website information faster instead of spending a lot of time downloading a HTML file.
One last reason using css is best practice is because css files can be reused for multiple web pages while inline HTML can only be used for one line of code.
This causes your work to look unorganized but also opens you up to a lot of mistakes when working with multiple lines of code.

## Prompt 4

Imagine you are teaching a brand new programmer a brief lesson about the `class` and `id` attributes in HTML as well as how to use them to style elements using CSS. Your lesson should have the following components:

- An explanation of the concept of "classes" and "ids" with an analogy.
- An example of the usage using an HTML code block and a CSS code block.
- An explanation of the syntax using the terms: **attribute**, **selector**

### Response 4

In HTML to build code we use elements. Elements is a term used to define the section of code that you want to create. To create an element you have to use a <starttag> followed by content of your choice followed by an <end tag>.
When describing elements, terms like ID and CLASS are used. The ID attribute is used to give a unique name to an element. The ClASS attribute is used when a user would like to group together multiple elements that have similar values.
To help make this a little easier to understand, let's try thinking about a train. The train represents the structure of code that is HTML. To drive the train there is one and can only be one person to drive the train. The "ID" of this person is the train conductor.
Now that you have that in mind, think about the body of a train. Does a train normally have 1 train car or 1 passenger? No! To build a complete train there are multiple train cars and multiple people in the train cars as well.
That is exactly what CLASS is, Classes are multiple sections of elements that are given the same name as a way to group these elements together because they have similar values.
//

- HTML
  <!DOCTYPE html>
  <html>
  <body>
  <h1 id="trips">Travel List</h1>
  <p class="favorite">Grenada</p>
  <p class="favorite">Japan</p>
  <p class="destination">Berlin</p>
  <p class="destination">Paris</p>
  <p class="destination">London</p>
  </body>
  </html>

- CSS
<html>
<body>
<h1>Names</h1>
<p>Ellen</p>
<p>Emily</p>
<p>Eudora</p>
<p>Edward</p>
<p>Eddie</p>
</body>
</html>

## Prompt 5

The Document Object Model (DOM) API provides functions for manipulating HTML documents. It is possible to build an entire website using only JavaScript and the DOM API, however is that the best practice?

When building a website, how can I decide which content I should write using HTML/CSS and which content I should create using the JavaScript and the DOM API?

### Response 5

-

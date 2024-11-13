// Q1

- A semantic element clearly describes its meaning to both the browser and the developer.
- non-semantic elements:
dont have any meanins and tells us nothing of what they contain
use class attribute to work with structure.
 <div> and <span> - Tells nothing about its content.
- <div id="nav"> <div class="header"> <div id="footer"> to indicate navigation, header, and footer.
- semantic elements: <form>, <table>, and <article> - Clearly defines its content.

[<article>

<aside>
<details>
<figcaption>
<figure>
<footer>
<header>
<main>
<mark>
<nav>
<section>
<summary>
<time>]
//
// Q2

- image alt text -the content of images, provide more info to rank higher in 'SERPs'[Search Engine Results Page] - page that appears after a user enters a search query in the search engine. ,
  original purpose was to add context for those who use screen readers (tech that helps ppl who have difficulties seeing have access to digital content (websites, application) via audio or touch) , for those who cannot access image shared on website. (low connection, broken link, low vision)
  read allowed or display alt text in place of image.
  (lieu - in place of)
  to implement alt image place alt attribute into img tag = <img src="image" alt="">,
  if no alt attribute , screen readers will read file name, the TITLE attribute if there is one, or it will skip over the img,
  add concise, clear alt text to all non-decorative img tags,

- well-structured html
  use semantic html tags to segment diff regions on the page,
  heading/subheading tags <h1>,<h2>,<h3>
  pragraphs <p>, number listed <ol>, non-numbered <ul>, nested listed items <li> ... etc ,
  DO NOT USE <div>, <span>,

- lang attribute
  more writing accessible HTML,
  place this on inside of opening html tag ex. <html lang='en'>,
  helps identify the prime language of a page (browser, search engines, translation software, and screen readers)
  to indicate language change u can add lang attribute in another tag <p>, <span>,
  lang attribute tells text to speech how to pronounce foreign words on the page.

- hyperlinks
  descriptive hyperlinks sharing information from a different web page,
  write link text that adequately describes where it leads and is unique from other link text.

- aria roles
  [Accessible Rich Internet Applications suite of web standards],
  set the standards that make user interface controls(elements that determine how data, text, images, and other info appear on user forms for both display and input) more accessible for ppl using assistive technologies.

//
// Q3
inline CSS used to apply a unique style for a single element.
how to use : add style attribute to the element of choice. the style attribute contains any css property.
? why might it be useful to write inline style.
? another argument on why you should use CSS in a separate file
//
not best practice to use inline in html because the style cannot be used anywhere else in the code, it will need to be repeated each time.
any internal styling in css would be override by any text set with inline styling.

advantage - inline sets precedence over all other styles.
quick and easy to use and helps with previewing work
dont need to create another file.
in js use style attribute

disadvantages - makes html structure look unorganized.
difficult to keep track off and cannot be resued.
this will affect the file size of your code which can increase the time it takes to run.
cannot be used to style elements or classes.

why use css - its reusable across multiple web pages.
helps to improve loading time, it can quickly retrieve css file rather then downloading the whole html file which will take longer.
while retriving the css file will be faster depending on internet connection the files may not be able to load.
can help with more complex designs bc its all done in one place.
best for large, multi page websites.

-

//
// Q4
elements = HTML elements <h1>,<p>,<body>,/ must have <starttag> content <endtag>

- id = mark element as a single, unique, important item on the page.
  !only one per page!

- class = to indicate multiple related elements on a page or website.
  !more than once!

- both can reference elements on page with either js or css
  both can be put both in a single tag <p id="" class=""> </p>

//
// Q5
? is it best practice to build a website using JS and DOM API
? how do know when to write using HTML & CSS, what is created when JS and DOM API
//
dom = html structure but in JS Object format => const h1 {
id : "",
tectContent: "
}

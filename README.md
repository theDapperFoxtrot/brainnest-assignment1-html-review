# brainnest-assignment1-html-review

Brainnest FD Training – Assignment 1
Terminology
1. What do HTML and CSS stand for? 
HyperText Markup Language and Cascading Styling Sheets

2. Would you rather use HTML or CSS, for putting paragraphs of text on a webpage?
Absolutely you would use HTML in order to render text onto a webpage. CSS is utilized when you’re styling elements. The only way you could use CSS to render content would be using pseudoselectors on an existing HTML element and the ‘content’ property.

3. Would you rather use HTML or CSS, to change the font and background color of a button? 
CSS would be leveraged here in order to change the appearance of the button, including the font and background color.

4. What is an HTML tag? 
A tag refers to the elements placed in HTML, and the tags themselves are the opening and closing tags respectively (unless that tag is an empty or self-closing element). e.g. `<p> </p> OR <img>`

5. What are the three parts of an HTML element? (image from paragraph) 
With the exception of self-closing elements, every element would have and opening and closing tag, as well as the content between them. e.g. `<p>This is how you would make a paragraph with content.</p>`

6. What is the purpose of the doctype declaration? 
The typical declaration for the doctype is `<!DOCTYPE html>` which informs the browser client that the document being served is formatted in HTML5.

7. What is the HTML element? 
The HTML element wraps the entirety of the page, except for the doctype declaration. This allows the browser to read and interpret the markup written between the opening and closing HTML tags.

8. What is the purpose of the head element? 
The head element contains meta data in order to inform the browser of information unrelated to what is rendered onto the page. The two important pieces of the `<head>` element are `<meta charset=”UTF-8”> and <title>Document</title>.`

9. What is the purpose of the body element? 
The body element contains content that can be rendered to the page, and the structure in which it is organized in the document object model. There are a number of semantic elements that can be used to create the initial layout of a web page before any styling or programming logic is added.

10. How do you create a paragraph in HTML? 
To create a paragraph in html, you utilize the opening and closing paragraph tags. `<p>Content here.</p>`

11. How do you create a heading in HTML? 
The main heading of a webpage can be created by using the main heading tags. `<h1>Heading</h1>`
	
12. How many different levels of headings are there and what is the difference between them? 
Namely the available tags are `<h1> through <h6>`. It is important that an `<h1>` only be used once per page to promote SEO. Otherwise, other heading tags can be reused and individually affected with styling by adding unique classes.

13. What element should you use to make text bold and important? 
In order to give importance to text content, utilize the following tags: `<strong>Important text</strong>.`

14. What element should you use to make text italicized to add emphasis to it? 
In order to give emphasis to text content, utilize the following tags: `<em>Emphasized text</em>.`

15. What relationship does an element have with any nested elements within it? 
The nested element is considered the child of the parent element. For example:
`<div class=”parent”>
	<p>Child.</p>
</div>`

16. What relationship do two elements have if they are at the same level of nesting? 
If two or more elements are connected at the same level of nesting, then they are considered to be siblings. For example:
`<div>
	<p>Sibling.</p>
	<p>Sibling.</p>
</div>`

17. How do you create HTML comments? 
An HTML comment is contained between the following symbols: `<!-- HTML comment here -->`

18. What HTML tag is used to create an unordered list? 
To create an unordered list, you not only need to have opening and closing tags for the list, but also the list items. Here’s an example:
`<ul>
	<li>Apples</li>
	<li>Bananas</li>
</ul>`

19. What HTML tag is used to create an ordered list? 
Similarly, to create an ordered list, you not only need to have opening and closing tags for the list, but also the list items. Here’s an example:

`<ol>
	<li>Apples</li>
	<li>Bananas</li>
</ol>`

20. What HTML tag is used to create list items within both unordered and ordered lists? 
As illustrated in the previous answers: `<li></li>`

21. What element is used to create a link? 
The anchor element enables a clickable link that requires a href=”” attribute to direct the user.

22. What is an attribute? 
Attributes are applied to elements to make use of the element’s potential features. While some attributes can be applied to all elements such as class, there are some attributes that are specific to certain elements.

23. What attribute tells links where to go? 
In the opening anchor tag, you would include the attribute href=”<insert address here>”

24. What is the difference between an absolute and relative link? 
An absolute link is one that will lead to the destination regardless of where the page is located within its file structure, say www.google.com for example. A relative link is rather telling by its name, but it is a link to a pager relative to where it is located in the file structure. If you have an index.html, and wish to link to an about_me.html that is nested within a folder called pages, you would apply the following: href=”./pages/about_me.html” to your opening anchor tag. 

25. Which element is used to display an image? 
To display an image, you would make use of the `<img>` tag. This tag is self-closing/empty and does not require a closing tag.

26. What two attributes do images always need to have? 
Every image needs to have the src=”” and the alt=””

27. How do you access a parent directory in a file path? 
To move up one directory to the parent, simply use two dots. For example:
`<a href=”../index.html”>Home</a>`

28. What are the four main image formats that you can use for images on the web?
.jpg, .png, .gif, .tif /.tiff

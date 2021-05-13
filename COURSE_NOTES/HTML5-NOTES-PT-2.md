# W3School-0005 Video Notes Pt 2


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the [HTML Video Playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB) listed in the project's README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).


### Web Browsers

13. The purpose of a web browser (Chrome, Edge, Firefox, Safari) is to read HTML documents and display them correctly.
	* A browser does not display the HTML tags, but uses them to determine how to display the document.

#### HTML Page Structure

14. Here is a diagram or visualization of an HTML page structure:

	```html
	┌────────────────────────────────────────────────────────────────────────────────────────────────────────────┐
	| <html>                                                                                                     |
	|  ┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐  |
	|  | <head>                                                                                               |  |
	|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
	|  |  | <title>Page title</title>                                                                      |  |  |
	|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
	|  | </head>                                                                                              |  |
	|  └──────────────────────────────────────────────────────────────────────────────────────────────────────┘  |
	|  ┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐  |
	|  | <body>                                                                                               |  |
	|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
	|  |  | <h1> This is the H1 Heading </h1>                                                              |  |  |
	|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
	|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
	|  |  | <p> This is H1's paragraph </p>                                                                |  |  |
	|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
	|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
	|  |  | <h2> This is the H2 Heading </h2>                                                              |  |  |
	|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
	|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
	|  |  | <p> This is H2's paragraph </p>                                                                |  |  |
	|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
	|  | </body>                                                                                              |  |
	|  └──────────────────────────────────────────────────────────────────────────────────────────────────────┘  |
	| </html>                                                                                                    |
	└────────────────────────────────────────────────────────────────────────────────────────────────────────────┘
	```
	* Note: The content inside the <body> section (the white area above) will be displayed in a browser. The content inside the `<title>` element will be shown in the browser's title bar or in the page's tab.

	* Some good links for learning HTML5 coding standards are:
		* [WHATWG HTML5 Living Standard](https://html.spec.whatwg.org/multipage/) 2012
		* [W3C Recommendation: HTML 5.1 2nd Edition](https://www.w3.org/TR/html51/) 2017
		* [W3C Recommendation: HTML5.2](https://www.w3.org/TR/html52/)

#### HTML Page Sections

15. Webpages have sections that help to break down the structure of the page and it's design.
	* The `<body>` section is the primary section of the web page.
	* The `<h1>` element is also a section of the webpage. It is the title of our first body section.


##### HTML Headings

16. HTML headings are defined with the `<h1>` to `<h6>` tags.
	* The `<h1>` defines the most important heading. `<h6>` defines the least important heading.


##### HTML Paragraphs
17. HTML paragraphs are defined with the `<p>` tag.
	* `<p>This is a paragraph.</p>`


##### HTML Links
18. HTML links are defined with the `<a>` tag..
	* An Example:
	```html
	<a href="https://www.omni-solutions-tech.com">Omni-Solutions Tec Link</a>
	```
	* The link's destination is specified in the `href` attribute.
	* Attributes are used to provide additional information about HTML elements.
	* You will learn more about attributes in a later chapter.

	###### HTML Images
19. HTML images are defined with the `<img>` tag.
	* The source file (`src`), alternative text (`alt`), `width`, and `height` are provided as attributes:
	```html
	<img src="https://omni-solutions-tech.net/imgs/omni-solutions-banner.jpg"
	alt="Image of Omni-Solutions Technology Consultants banner" width="1947" height="555">
	```

#### How to View HTML Source?

20. View HTML Source Code.
	* To view HTML source, *Right-click* in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

21. Inspect an HTML Element.
	* To inspect an HTML element on a page, *Right-click* on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

#### HTML Elements

22. As discussed in *HTML5-NOTES-PT1, Section 5.* An HTML element is defined by a start tag (`<element>`), some content, (This is my content) and an end tag (`</element>`).
	* The HTML element is everything from the start tag to the end tag:
	```html
	<tagname>Content goes here...</tagname>
	```
	* Examples of some HTML elements:
	```html
	<h1>My First Heading</h1>
		<p>My first paragraph.</p>
	```
	* Not covered in *Section 5.* and *Section 6.* is an example of how the Nested Elements are represented in the code itself. Here we have an example of a basic HTML page:
	```html
	<!DOCTYPE html>
	<html>
	   <body>
	      <h1>My First Heading</h1>
	      <p>My first paragraph.</p>
	    </body>
	</html>
	```

	* We know that the <html> element is the root element and it *defines* the whole HTML document.
	* We should by now already know that it has a start tag `<html>` and an end tag `</html>`
	* Nested inside the `<html>` element there is a `<body>` element:
	```html
	<body>

		<h1>My First Heading</h1>
			<p>My first paragraph.</p>

	</body>
	```

	* The `<body>` element defines the document's body.
	* Then, inside the `<body>` element there are two other elements: `<h1>` and `<p>` as seen here:
	```html
	<h1>My First Heading</h1>
		<p>My first paragraph.</p>
	```


#### Never Skip the End Tag

23. Some HTML elements will display correctly, even if you forget the end tag:
	```html
	<p>This is a paragraph
	```
	* However, never rely on this! Unexpected results and errors may occur if you forget the end tag!
	* For a complete list of all available HTML tags, visit W3School's [HTML Tag Reference](https://www.w3schools.com/tags/default.asp).


#### Conclusion
This concludes Part 2 of the Notes on HTML5 Coursework for the Video Course and information from W3Schools.com. Please move on to the next document [HTML-NOTES-PT-3.md](https://github.com/AdamRj-765/W3School-0005/blob/master/COURSE_NOTES/HTML5-NOTES-PT-3.md).

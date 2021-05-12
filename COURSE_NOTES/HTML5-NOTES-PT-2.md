# W3School-0005 Video Notes Pt 2


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the HTML video course provided in the README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).

For this project, we will be using GitHub's version control to document the progress of the test environment that is needed, and which documents the progress of our understanding of HTML5 custom code development and design process. It will be a living document that will be added to and redesigned on-the-fly by your instructors in order to be a more up to date knowledgebase of the latest HTML5, CSS3 and JavaScript languages and their standards.

We will start with information and notes from both the Video Tutorials referenced in the README.md for the project and it is recommended that you watch the video referenced in this document as well as reading from the [W3Schools.com's](https://www.w3schools.com/) wonderful HTML Tutorial Course and online reference documents, as well as noting the information in this document.


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

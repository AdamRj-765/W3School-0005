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
18. HTML links are defined with the `<a>` tag.
	* An Example:
	```html
	<a href="https://www.omni-solutions-tech.com">Omni-Solutions Tec Link</a>
	```
	* The link's destination is specified in the `href` attribute.
	* Attributes are used to provide additional information about HTML elements.
	* You will learn more about attributes in a later chapter.

	* Personal Note: Some links are for specific pages or links to files, images, media, etc. that can be local, or located within the file system that the referring page (the page you are creating the link on) is in on the same web server that is hosting the website you are developing.
	* In this case you do not need to use a full URL for the ` <a href=" "` attribute value.

	* **Example 1**
		* Here is an example of a link to an external page that is **NOT** included in the site's file system which has a domain name of `omni-solutions-tech.com`. Here the domain name points to the Document Root of the site and is the root folder of the website.
		* If the referring page (the webpage that we are linking from in this case `index-1.html`), is **IN** the *Document Root* (the website's root folder), and the link is to another page that is **NOT** a page within the file system of the website, we must use the full URL for external website's page we want to link to. This includes the domain name and the path to the file within that domain's file structure such as Google's homepage as seen below:
			```html
			<!DOCTYPE html>
			<html lang="en">
			   <head>
			      <meta charset="utf-8"/>
			      <title>Omni-Solutions Tech </title>
			   </head>
			   <body>
			      <a href="https://google.com.com">Link to Google Search Engine Homepage</a>
			   </body>
			</html>
			```
			* Note: The **domain** of the site were linking to is not the same domain as the domain that our referring page is in. Our page is in the Document Root of the domain, `omni-solutions-tech.com`, therefore we MUST use a full URL to link to Google's page. (The `index.html` page is not needed because when going to a domain, the `index.html` page of any site is by default always given first).

	* **Example 2**
		* Here is an example of a **URL link** to a page that **IS** located in the same site. Normally it would be located in the site's **Document Root** or one of it's subfolders. 	In other words it is not in a parent folder but either the same of one of it's child folders.
		* If our referring page is in the **Document Root** and the page that we are linking **TO** is in the same directory or a sub-directory of the **Document Root**, then we can link to it in two ways. In the example below, the referring document is the page we are linking **FROM** and we will call it `index-1.html` and the page we will be linking **TO**, which is a page in our site that we will call `index-2.html` located in  the `<document-root>/pages` folder or if it were live it would be located on the web at `https://omni-solutions-tech.com/pages/` If there are more than one webpages in the `/pages/` folder, and since the filename is not `index.html`, then we must name which file we want to link to and in this case the file name is `index-2.html`:

	```html
	<!DOCTYPE html>
	<html lang="en">
	   <head>
	     <meta charset="utf-8"/>
	     <title>Omni-Solutions Tech </title>
	   </head>
	   <body>
	     <a href="https://www.omni-solutions-tech.com/pages/index-2.html">Omni-Solutions Tech Page 2 Link</a>
	   </body>
	 </html>
	```
	* Here is the filesystem diagram of where the two files are located in relation to each other. Again the referring page is the index.html page located in the document root here seen as the `public_html`
	```
	<omni-solutions-tech.com>/
	├── public_html/
	|   ├── pages/
	|   |    └── index2.html
	|   └── index.html
	└── index3.html

	```


	```html
	<!DOCTYPE html>
	<html lang="en">
	   <head>
	      <meta charset="utf-8"/>
	      <title>Omni-Solutions Tech </title>
	   </head>
	   <body>
	      <a href="pages/index2.html">Omni-Solutions Tech Page 2 Link</a>
	   </body>
	</html>
	```

	* Note: the `<base href=" "` element. In this case it is the domain name which points to the Document Root. The **HTML** `<base>` **element** specifies the base URL to use for all relative URLs in a document. There can be only one `<base>` element in a document. In this case, the `<base href=" "` meta element is not needed as the process is done by default without the meta element. And this only works for when a site is live and has a domain.
	* If there is a page that needs to be linked to that is in a parent folder the `<a href=" "></a>` link inside would need to have this for a folder that is in the same parent folder as your referring page as seen here in this file system where the referring page is `index-1.html`:
	```
	<omni-solutions-tech.com>/
	├── public_html/
	|   ├── pages-1/
	|   |    └── index-1.html
	|   └── index.html
	└── index3.html

	```



	* The second example of the local link can also be linked to without using the domain name for the site the referring page is a part of.
**Example** If the page is live on a webserver and your referring page is in the **Document Root**, you can refer to the other page by doing this version of the above full URL:
	```html
	<a href="/pages/index2.html">Omni-Solutions Tech Link to one of it's pages</a>
	```

	      <base href="https://omi-solutions-tech.com/" />


See the Personal notes on External Links and Local Links in [HTML5-NOTES-PT3.md](https://github.com/AdamRj-765/W3School-0005/blob/20210507T1442Zm6/COURSE_NOTES/HTML5-NOTES-PT-3.md)


###### HTML Images
19. HTML images are defined with the ```<img>``` tag.
	* The source file (```src```), alternative text (```alt```), ```width```, and ```height``` are provided as attributes:
	```
	<img src="https://omni-solutions-tech.net/imgs/omni-solutions-banner.jpg" alt="Image of Omni-Solutions Technology Consultants banner" width="1947" height="555">
	```

#### How to View HTML Source?

20. View HTML Source Code.
	* To view HTML source, *Right-click* in an HTML page and select "View Page Source" (in Chrome) or "View Source" (in Edge), or similar in other browsers. This will open a window containing the HTML source code of the page.

21. Inspect an HTML Element.
	* To inspect an HTML element on a page, *Right-click* on an element (or a blank area), and choose "Inspect" or "Inspect Element" to see what elements are made up of (you will see both the HTML and the CSS). You can also edit the HTML or CSS on-the-fly in the Elements or Styles panel that opens.

#### HTML Elements

22. As discussed in *HTML5-NOTES-PT1, Section 5.* An HTML element is defined by a start tag (```<element>```), some content, (This is my content) and an end tag (```</element>```).
	* The HTML element is everything from the start tag to the end tag:
	```
	<tagname>Content goes here...</tagname>
	```
	* Examples of some HTML elements:
	```
	<h1>My First Heading</h1>
		<p>My first paragraph.</p>
	```
	* Not covered in *Section 5.* and *Section 6.* is an example of how the Nested Elements are represented in the code itself. Here we have an example of a basic HTML page:
	```
	<!DOCTYPE html>
	<html>
		<body>

			<h1>My First Heading</h1>
				<p>My first paragraph.</p>

		</body>
	</html>
	```
	* We know that the <html> element is the root element and it *defines* the whole HTML document.
	* We should by now already know that it has a start tag ```<html>``` and an end tag ```</html>```
	* Nested inside the ```<html>``` element there is a ```<body>``` element:
	```
	<body>

		<h1>My First Heading</h1>
			<p>My first paragraph.</p>

	</body>
	```
	* The ```<body>``` element defines the document's body.
	* Then, inside the ```<body>``` element there are two other elements: ```<h1>``` and ```<p>``` as seen here:
	```
	<h1>My First Heading</h1>
		<p>My first paragraph.</p>
	```


#### Never Skip the End Tag

23. Some HTML elements will display correctly, even if you forget the end tag:
	```
	<p>This is a paragraph
	```
	* However, never rely on this! Unexpected results and errors may occur if you forget the end tag!
	* For a complete list of all available HTML tags, visit W3School's [HTML Tag Reference](https://www.w3schools.com/tags/default.asp).


#### Conclusion
This concludes Part 2 of the Notes on HTML5 Coursework for the Video Course and information from [W3Schools.com](https://www.w3schools.com/). Please move on to the next document [HTML-NOTES-PT-2.md](https://github.com/AdamRj-765/W3School-0005/blob/branch-210426T2301/COURSE_NOTES/HTML5-NOTES-PT-2.md).

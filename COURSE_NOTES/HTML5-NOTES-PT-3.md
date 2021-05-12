# W3School-0005 Video Notes Pt 3


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the HTML video course provided in the README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).

For this project, we will be using GitHub's version control to document the progress of the test environment that is needed, and which documents the progress of our understanding of HTML5 custom code development and design process. It will be a living document that will be added to and redesigned on-the-fly by your instructors in order to be a more up to date knowledgebase of the latest HTML5, CSS3 and JavaScript languages and their standards.

We will start with information and notes from both the Video Tutorials referenced in the README.md for the project and it is recommended that you watch the video referenced in this document as well as reading from the [W3Schools.com's](https://www.w3schools.com/) wonderful HTML Tutorial Course and online reference documents, as well as noting the information in this document.


#### HTML Attributes

24. HTML attributes provide additional information about HTML elements.
	* HTML Attributes
		* All HTML elements can have **attributes**
		* Attributes provide **additional information** about elements
		* Attributes are always specified in **the start tag**
		* Attributes usually come in name/value pairs like: **name="value"**

26. The href Attribute
	* The `<a>` tag defines a hyperlink. The `href` attribute specifies the URL of the page the link goes to:
	```html
	<a href="https://www.omni-solutions-tech.com">Omni-Solutions Tech Link</a>
	```
	* You will learn more about links in our [HTML Links chapter](https://www.w3schools.com/html/html_links.asp).

27. The src Attribute
	* The `<img>` tag is used to embed an image in an HTML page. The `src` attribute specifies the path to the image to be displayed:
	```html
	<img src="img_girl.jpg">
	```
	* There are two ways to specify the URL in the `src` attribute:
		1. **Absolute URL** - Links to an external image that is hosted on another website. Example: src="https://www.omni-solutions-tech.com/imgs/omni-solutions-banner.jpg".
		* Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.
		2. **Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name. If the URL begins without a slash, it will be relative to the current page. **Example:** `src="img-1.jpg"`. If the URL begins with a slash, it will be relative to the domain. **Example:** `src="/imgs/image-1.jpg"`.
		* Tip: It is almost always best to use relative URLs. They will not break if you change domain.

		* Personal Note: When using **Relative URL**s, we have tested developing websites on a local file system of a PC and tested uploading the site files to a remote Apache 2.x Web Server. When using a Windows 10 file system, we  noticed that if we include the first forward slash (`/`) in the `src` attribute, the link would not work.
		* Let us say that during a development test on a local PC, we need to link to an image from our **Main Page**, **Homepage**, or any page you may be linking from that is in our test website.
		* For our test we will refer to our **Home Page** as the index page with the filename `index-1.html` that will be located in the `public_html/` folder and the image will be called `image-1.jpg`, and will be located in the `images/` folder.
		* Also this site's development site files will be located on our PC's local `C:/` Drive on a system running Windows 10 in a folder called `omni-solutions-tech` Our simulated **Document Root** will be the `public_html` folder. Please see the following local Web Site development file system schematic:
			```
			├── omni-solutions-tech/
			|   ├── public_html/
			|   |    └── images/
			|   |       └── image-1.jpg
			|   └── index-1.html
			```

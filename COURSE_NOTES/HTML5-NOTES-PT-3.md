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
* The ```<a>``` tag defines a hyperlink. The ```href``` attribute specifies the URL of the page the link goes to:
```
<a href="https://www.omni-solutions-tech.com">Omni-Solutions Tec Link</a>
```
* You will learn more about links in our [HTML Links chapter](https://www.w3schools.com/html/html_links.asp).

27. The src Attribute
* The ```<img>``` tag is used to embed an image in an HTML page. The ```src``` attribute specifies the path to the image to be displayed:
```
<img src="img_girl.jpg">
```
* Personal Note: ```src``` attributes for images can be an external link as well as internal or local links or locally hosted link. With external links, the ```src``` attribute will be a URL. Although you can still use the URL for the file your calling in the link, you have to treat the URI differently  








	* Personal Note: Some links are to pages or other files that are **NOT** located in your site files, or located on an external web server. These are called **external links**. Other are local, or located in the same site files or within the local file system that the referring page (the page you are creating the link on "index-1.html") is in. They are called   on the same web server that is hosting the website you are developing.
	* In this case you do not need to use a full URL for the ` <a href=" "` attribute value.

	* **Example 1**
		* Here is an example of a link to an external page that is **NOT** included in the site's file system which has a domain name of `omni-solutions-tech.com`. Here the domain name points to the Document Root of the site and is the root folder of the website.
		* If the referring page (the webpage that we are linking from in this case `index-1.html`), is **IN** the *Document Root* (the website's root folder), and the link is to another page that is **NOT** a page within the file system of the website, we must use the full URL for external website's page we want to link to. This includes the domain name and the path to the file within that domain's file structure such as Google's homepage as seen below:
			```html
			<!-- index-1.html -->
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

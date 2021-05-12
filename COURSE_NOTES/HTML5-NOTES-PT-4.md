




# Test
















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

* Note: The content inside the <body> section (the white area above) will be displayed in a browser. The content inside the ```<title>``` element will be shown in the browser's title bar or in the page's tab.

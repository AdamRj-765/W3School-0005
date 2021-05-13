# W3School-0005 Video Notes Pt 3


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the [HTML Video Playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB) listed in the project's README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).

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
	<img src="image-1.jpg">
	```
	* There are two ways to specify the URL in the `src` attribute:
		1. **Absolute URL** - Links to an external image that is hosted on another website. Example: src="https://www.omni-solutions-tech.com/imgs/omni-solutions-banner.jpg".
		* Notes: External images might be under copyright. If you do not get permission to use it, you may be in violation of copyright laws. In addition, you cannot control external images; it can suddenly be removed or changed.
		2. **Relative URL** - Links to an image that is hosted within the website. Here, the URL does not include the domain name.
			* If the URL begins without a slash, it will be relative to the current page. **Example:** `src="img-1.jpg"`.
			* If the URL begins with a slash, it will be relative to the domain. **Example:** `src="/imags/image-1.jpg"`.
		* Tip: It is almost always best to use relative URLs. They will not break if you change domain.

		* Let us say that during a development test on a local PC, we need to link to an image from our **Main Page**, **Homepage**, or any page you may be linking from that is in our test website.
		* Note: When using **Relative URLs**, many times the development process is done on a local file system before uploading the site files to a remote Web Server who's *Document Root* will be mapped to a domain name. In order to test sites locally before going *Live* with the site, one must use **Relative URLs** until going live unless using a trick on the test device that involves editing the hosts file. We recommend however, not editing the test device's host file but instead using **Relative URLs**.  The following information describes how to link to site files located on a local filesystem and then change the links after going *live*.

		* As pointed out above, if the **Relative URL** includes the first forward slash (`/`) in the `src` attribute, the link would not work when testing links on a local PC's filesystem because there is no domain. So we **MUST** exclude the first forward slash (`/`) for all your links because they will all need to be relative in some way to the current page.
		* **Example 1**
			* For our example we will call our current page `index-1.html` that will be located in the root folder `public_html/` and the image we will link to will be called `image-1.jpg`, and it will be located in the `images/` folder.
			* Our simulated **Document Root** will be the `public_html` folder. Here is the local development Web Site file system schematic for this example:
				```
				├── C:/
				|   ├── public_html/
				|   |    └── images/
				|   |       └── image-1.jpg
				|   └── index-1.html <----------current page
				```
			* Here is the code for our index-1.html file:
				```html
				<!-- index-1.html -->
				<!DOCTYPE html>
				<html lang="en">
			      <head>
			         <meta charset="utf-8"/>
			         <title>Index-1 Page </title>
			      </head>
			      <body>
			         <img src="images/image-1.jpg" alt="Omni-Solutions Tech">
			      </body>
				</html>
				```
			* When double clicking on the `index-1.html` file you should see the page load in your default browser with the Omni-Solutions Tech image that is properly linked in your page.

		* **Example 2**
		 	* If you decide to work on a different web page that is located inside a child folder of the simulated Document Root such as a folder called `pages/` and your current page is a page called `index-2.html` located in that folder as seen below:
				```
				├── C:/
				|   ├── public_html/
				|   |   ├── pages/
				|   |   |   └── index-2.html <----------current page
				|   |   └── images/
				|   |       └── image-1.jpg
				|   └── index-1.html
				```
			* In this case, in order to link to a same level sub directory as the folder your current page is in, you would need to use a *double-dot-slash* (`../`) to indicate that it is in another folder.
			* Here is the code for your `index-2.html` file that links to the image in an adjacent directory in your local file system:
			```html
			<!-- index-2.html -->
			<!DOCTYPE html>
			<html lang="en">
			   <head>
			      <meta charset="utf-8"/>
			      <title>Index-2 Page </title>
			   </head>
			   <body>
			      <img src="../images/image-1.jpg" alt="Omni-Solutions Tech">
			   </body>
			</html>
			```
		* **Example 3**
		 	* If you are needing to make a **Relative URL** to a file that is located in the parent folder that your current file is located in, you simply need to use the single *dot-slash* (`./`)to achieve this. In other words, if you need to link to `index-1.html` from `index-2.html` you can use this code to make a link to your own page using a **Relative URL**. Again here is your file system schema:
				```
				├── C:/
				|   ├── public_html/
				|   |   ├── pages/
				|   |   |   └── index-2.html <----------current page
				|   |   └── images/
				|   |       └── image-1.jpg
				|   └── index-1.html
				```
			* And here is your new code for `index-2.html`
			```html
			<!-- index-2.html -->
			<!DOCTYPE html>
			<html lang="en">
			   <head>
			       <meta charset="utf-8"/>
			       <title>Index-2 Page </title>
			   </head>
			   <body>
			       <a href="./pages/index2.html">Page 2</a>
			   </body>
			</html>
			```

			#### Conclusion
			This concludes Part 3 of the Notes on HTML5 Coursework for the Video Course and information from W3Schools.com. Please move on to the next document [HTML-NOTES-PT-4.md](https://github.com/AdamRj-765/W3School-0005/blob/master/COURSE_NOTES/HTML5-NOTES-PT-4.md).

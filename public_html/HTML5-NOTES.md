# W3School-0005 Video Notes

## INTRODUCTION

These notes will provide the information I have compiled and deemed helpful to me in understanding the information given in both the HTML video course provided in the README.md, and from the HTML online tutorials from W3Schools.com.

For this project, I am using GitHub's version control to document the progress of the test environment that is needed to  which documents the progress of my understanding of HTML5 custom code development and design. It will be a living document that I will add to and redesign on the fly in order to be a more up to date knowledgebase of the latest HTML language.

We will start with information and notes from both the Video Tutorials I am watching, and from [W3Schools.com's](https://www.w3schools.com/) wonderful courses and online reference  documents.

### Video 1

#### HTML Documents

1. HTML is the standard markup language for creating Web pages.

##### What is HTML?

 * HTML stands for Hyper Text Markup Language
 * HTML is the standard markup language for creating Web pages
 * HTML describes the structure of a Web page
 * HTML consists of a series of elements
 * HTML elements tell the browser how to display the content
 * HTML elements label pieces of content such as "this is a heading", "this is a paragraph", "this is a link", etc.


##### The <!DOCTYPE> Declaration

1. The ```<!DOCTYPE>``` declaration represents the document type, and helps browsers to display web pages correctly. It declaration defines that this document is an HTML5 document.

	* All HTML documents must start with a ```<!DOCTYPE>``` declaration and the declaration is not really an HTML tag. It is an "information" declaration to the browser about what document type to expect.

	* The ```<!DOCTYPE>``` declaration is also not case sensitive so browsers will accept ```<!DOCTYPE>``` as the same as ```<!doctype>```.

	* It must only appear once, at the top of the page (before any HTML tags).
		* Browsers read in a top down manor. They must see the ```<!DOCTYPE>``` declaration first, and then move on down through the rest of the code line by line so it must be declared before any elements.
		* In older documents (HTML 4 or XHTML), the declaration is more complicated because the declaration must refer to a DTD (Document Type Definition).
			* The ```<!DOCTYPE>``` declaration for HTML 4.01 is:
			```
			<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
			```
			* The ```<!DOCTYPE>``` declaration for XHTML 1.1 is:
			```
			<!DOCTYPE html PUBLIC "-//W3C//DTD XHTML 1.1//EN" "http://www.w3.org/TR/xhtml11/DTD/xhtml11.dtd">
			```
			* The ```<!DOCTYPE>``` declaration for HTML5 is:
			```
			<!DOCTYPE html>
			```
			* Currently all modern browsers will recognize the ```<!DOCTYPE html>``` declaration as an instruction to use the latest version of HTML and will render the page as such. It will use the latest version of HTML whatever it is and will do so for future HTML versions. With the ```<!DOCTYPE html>``` declaration developers no longer need to specify a version number.

##### The HTML Element

4. An HTML element is defined by a start tag, some content, and an end tag: ```<tagname>Content goes here...</tagname>```


* Examples of some HTML elements:

```
<h1>My First Heading</h1>
```
```
<p>My first paragraph.</p>
```

* Note: Some HTML elements have no content (like the ```<br>``` element). These elements are called **empty** elements. **Empty** elements do not have an end tag!

##### Nested HTML Elements

5. HTML elements can be nested (this means that elements can contain other elements).

* All HTML documents consist of nested HTML elements.

* The <html> element is the root element and it defines the whole HTML document.

* Inside the <html> element there are other elements such as ```<head>```, ```<body>```, ```<h1>```, and ```<p>``` elements.

##### Empty HTML Elements
6. Some HTML elements will display correctly, even if you forget the end tag such as the paragraph tag: ```<p>```  however, never rely on this! Unexpected results and errors may occur if you forget the end tag!

* There are also what are called **empty elements** that are HTML elements with no content such as the line break tag ```<br>``` .
* Here is an example of a paragraph tag that is properly closed with it's content inside the open and closing tags, but also with an empty element inside the paragraph tag:

```
<p>This is a <br> paragraph with a line break.</p>
```
* HTML tags are not case sensitive: ```<P>``` means the same as ```<p>```
* The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.

##### The HTML <html> Tag

7. The HTML document itself begins with an ```<html>``` **open tag** and ends with an ```</html>``` **closeing tag**. The **HTML** open ```<html>``` and closing ```</html>``` tags and the items inside are collectively called an **element** but they are not considered a **section** of the webpage. The ```<html>``` element represents the root of an HTML document.
	* Note: You should always include the lang attribute inside the <html> tag, to declare the language of the Web page. This is meant to assist search engines and browsers. Here is an example of an ```<html>``` **open tag** with the lang attribute to declare that English be used:
	```
	<html lang="en">
	```

##### The HTML <head> Tag

8. The **head** element ```<head> </head>```, is our first *real* Section. Inside the **head** element will be items that are not visible in the markup of the document. They include the **title** tag, any **meta tags**, and **JavaScript Refences**. Among them is also the **viewport** meta tag.

9. The body section is the primary section of the web page.

10. The h1 element is also a section of the webpage. It is the title of our first body section.

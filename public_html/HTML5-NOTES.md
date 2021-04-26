# W3School-0005 Video Notes

## INTRODUCTION

These notes will provide the information I have compiled and deemed helpful to me in understanding the information given in both the HTML video course provided in the README.md, and from the HTML online tutorials from [W3Schools.com's](https://www.w3schools.com/).

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

2. The ```<!DOCTYPE>``` declaration represents the document type, and helps browsers to display web pages correctly. It's declaration defines that your markup document is an HTML5 document.
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
		* Currently all modern browsers will recognize the ```<!DOCTYPE html>``` declaration as an instruction to use the latest version of HTML and will render the page as such. It will use the latest version of HTML (whatever it is), and will do so for future HTML versions. With the ```<!DOCTYPE html>``` declaration developers no longer need to specify a version number for their HTML source code to the browser.

##### The HTML <html> Tag Element

3. The  **HTML** ```<html>``` **Tag** is an **HTML** element, and it is also the *root element* of an HTML page. Although the **HTML** ```<html>``` **Tag** is an **HTML** element itself, it is not the only **HTML** element in a webpage. It is the container for all other **HTML** elements (except for the ```<!DOCTYPE>``` declaration).
	* There is only one **HTML** ```<html>``` **Tag** on a webpage and the other elements inside the **HTML** ```<html>``` **Tag** element are called **HTML** elements, but they are not *the* **HTML** element. *The* **HTML** that is the *root element* can only occur once in a webpage and needs to be just after the ```<!DOCTYPE>``` declaration.
	* The HTML document itself begins with an ```<html>``` **open tag** and ends with an ```</html>``` **closeing tag**.
	* The **HTML** open ```<html>``` and closing ```</html>``` tags and the items inside are collectively called an **element** but they are not considered a **section** of the webpage.

	* Note: You should always include the *lang* attribute inside the ```<html>``` tag, to declare the language of the Web page. This is meant to assist search engines and browsers. The following code shows how to reference a the English language using the *lang* attribute inside the ```<html>``` tag:
	```
	<html lang="en">
	```

##### HTML Elements

4. An **HTML** element is defined by a start tag, some content, and an end tag as seen here: ```<tagname>Content goes here...</tagname>``` .
	* Examples of some HTML elements:
	```
	<h1>My First Heading</h1>
	```
	```
	<p>My first paragraph.</p>
	```
	* HTML tags are not case sensitive: ```<P>``` means the same as ```<p>```
	* The HTML standard does not require lowercase tags, but W3C recommends lowercase in HTML, and demands lowercase for stricter document types like XHTML.
	* Note: Some **HTML** elements have no content (like the ```<br>``` element). These elements are called **empty** elements. **Empty** elements do not have an end tag!

##### Empty HTML Elements

5. Some HTML elements will display correctly, even if you forget the end tag such as the paragraph tag: ```<p>```  however, never rely on this! Unexpected results and errors may occur if you forget the end tag!
	* There are also what are called **empty elements** that are HTML elements with no content such as the line break tag ```<br>``` .
	* Here is an example of a paragraph tag that is properly closed with it's content inside the open and closing tags, but also with an empty element inside the paragraph tag:

	```
	<p>This is a <br> paragraph with a line break.</p>
	```

##### Nested HTML Elements

6. HTML elements can be nested (this means that elements can contain other elements).
	* All HTML documents consist of nested HTML elements.
	* The <html> element is the root element and it defines the whole HTML document.
	* Inside the <html> element there are other elements such as ```<head>```, ```<body>```, ```<h1>```, and ```<p>``` elements.


##### The HTML <head> Tag

7. The **head** ```<head> </head>``` element contains meta information about the HTML page. It is our first *real* Section and is simply a container for **metadata** (data about data).
	* The **head** ```<head> </head>```element is placed between the ```<html>``` tag and the ```<body>``` tag.
	* Inside the **head** element will be items that are not visible in the markup of the document.
	* Those items are sometimes called called  **meta tags**, **meta elements**, or **meta information**.
	* They include items like:
	 	* The HTML **title** ```<title>``` meta tag Element
		* The HTML **style** ```<style>``` meta tag Element
		* Any **JavaScript** refence links.
		* And the **viewport** meta tag. Which handles the responsiveness of the page and allows the scalability of the **viewport** , the user's visible area of a web page on a display device.




8. The body section is the primary section of the web page.

9. The h1 element is also a section of the webpage. It is the title of our first body section.

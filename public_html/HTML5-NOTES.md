# W3School-0005 Video Notes

## INTRODUCTION

These notes will provide the notes I have compiled for understanding the HTML video course outlined in the README.md for this project which documents the progress of my understanding of HTML5 custom code development and design. It will be a living document that I will add to and redesign on the fly in order to be a more up to date knowledgebase of the latest HTML language.

We will start with information and notes from both the Video Tutorials I am watching, and from [W3Schools.com's](https://www.w3schools.com/) wonderful courses and online reference  documents.

### Video 1

#### HTML Documents

1. The ```<!DOCTYPE>``` declaration represents the document type, and helps browsers to display web pages correctly. All HTML documents must start with a ```<!DOCTYPE>``` declaration. The declaration is not an HTML tag. It is an "information" declaration to the browser about what document type to expect. The ```<!DOCTYPE>``` declaration is also not case sensitive so ```<!DOCTYPE>``` is the same as ```<!doctype>``` to any browser.

*
 * It must only appear once, at the top of the page (before any HTML tags).

* 
 * In older documents (HTML 4 or XHTML), the declaration is more complicated because the declaration must refer to a DTD (Document Type Definition). Here is an example of an HTML 4 ```<!DOCTYPE>``` declaration:

```
<!DOCTYPE HTML PUBLIC "-//W3C//DTD HTML 4.01 Transitional//EN" "http://www.w3.org/TR/html4/loose.dtd">
```




* Currently all modern browsers will recognize the <!DOCTYPE html> to be what ever the latest version of HTML is being used and render it as such.

* Browsers read in a top down manor. They see the ```<!DOCTYPE>``` declaration first, and then move on down through the rest of the code line by line so it must be declared before any elements. Use it as the first item at the top of the document.

*

The <!DOCTYPE> declaration for HTML5 is: ```<!DOCTYPE html>```

3. The **HTML** open ```<html>``` and closing ```</html>``` tags and the items inside are called an **Element** but they are not considered a Section of the webpage.

4. The **Head Element** (<head> </head> ), is our first *real* Section. Inside the **Head Element** will be items that are not visible in the markup of the document. They include the **title** tag, any **meta tags**, and **JavaScript Refences**.

5. The body section is the primary section of the web page.

6. The h1 element is also a section of the webpage. It is the title of our first body section.


**

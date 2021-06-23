# W3School-0005 - HTML5 NOTES-PT-9


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the [HTML Video Playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB) listed in the project's README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).


## HTML Styles - CSS

CSS stands for Cascading Style Sheets.
 * CSS saves a lot of work. It can control the layout of multiple web pages all at once.


### What is CSS?

Cascading Style Sheets (CSS) is used to format the layout of a webpage.
 * With CSS, you can control the color, font, the size of text, the spacing between elements, how elements are positioned and laid out, what background images or background colors are to be used, different displays for different devices and screen sizes, and much more!

 * **Tip**: The word cascading means that a style applied to a parent element will also apply to all children elements within the parent. So, if you set the color of the body text to "blue", all headings, paragraphs, and other text elements within the body will also get the same color (unless you specify something else)!

#### Using CSS

CSS can be added to HTML documents in 3 ways:
 * **Inline** - by using the `style` attribute inside HTML elements
 * **Internal** - by using a `<style>` element in the <head> section
 * **External** - by using a `<link>` element to link to an external CSS file

The most common way to add CSS, is to keep the styles in external CSS files. However, in this tutorial we will use inline and internal styles, because this is easier to demonstrate, and easier for you to try it yourself.

#### Inline CSS

An inline CSS is used to apply a unique style to a single HTML element.
 * An inline CSS uses the s`style` attribute of an HTML element.
 * The following example sets the text color of the `<h1>` element to blue, and the text color of the `<p>` element to red:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <h1 style="color:blue;">A Blue Heading</h1>
     <p style="color:red;">A red paragraph.</p>
 </body>

 </html>
 ```

#### Internal CSS

An internal CSS is used to define a style for a single HTML page.
 * An internal CSS is defined in the `<head>` section of an HTML page, within a `<style>` element.
 * The following example sets the text color of ALL the `<h1>` elements (on that page) to blue, and the text color of ALL the `<p>` elements to red. In addition, the page will be displayed with a "powderblue" background color:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <head>
   <style>
     body {background-color: powderblue;
     }

     h1   {color: blue;
     }

     p    {color: red;
     }
   </style>
 </head>

 <body>
   <h1>This is a heading</h1>
   <p>This is a paragraph.</p>
 </body>
 </html>
 ```

#### External CSS

An external style sheet is used to define the style for many HTML pages.
 * To use an external style sheet, add a link to it in the `<head>` section of each HTML page:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <head>
   <link rel="stylesheet" href="styles.css">
 </head>

 <body>
   <h1>This is a heading</h1>
   <p>This is a paragraph.</p>
 </body>

 </html>
 ```
 * The external style sheet can be written in any text editor. The file must not contain any HTML code, and must be saved with a .css extension. The relative link for this file links to a file that is in the same folder as the html file linking to it. This is a relative path. A more common practice is to put .css files into folder unto themselves usually called "css".  In that event the `href` property value would be a relative link that would look like this:

 ```html
 <!DOCTYPE html>
 <html>

 <head>
   <link rel="stylesheet" href="css/styles.css">
 </head>

  <body>
   <h1>This is a heading</h1>
   <p>This is a paragraph.</p>
 </body>

 </html>
 ```



#### Conclusion
This concludes Part 9 of the Notes on HTML5 Coursework for the Video Course and information from W3Schools.com. Please move on to the next document [HTML-NOTES-PT-10.md](https://github.com/AdamRj-765/W3School-0005/blob/master/COURSE_NOTES/HTML5-NOTES-PT-10.md).

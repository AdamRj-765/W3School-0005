
# W3School-0005 - HTML5 NOTES-PT-8


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the [HTML Video Playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB) listed in the project's README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).


## HTML Comments

HTML comments are not displayed in the browser, but they can help document your HTML source code.


### HTML Comment Tags

You can add comments to your HTML source by using the following syntax:
 * Example:
 ```html
 <!-- Write your comments here -->
 ```
 * Notice that there is an exclamation point (!) in the start tag, but not in the end tag.
 * **Note**: Comments are not displayed by the browser, but they can help document your HTML source code.
 * With comments you can place notifications and reminders in your HTML code:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>
 <body>
 <!-- This is a comment -->
   <p>This is a paragraph.</p>
 <!-- Comments are not displayed in the browser -->
 </body>
 </html>
 ```
Comments are also great for debugging HTML, because you can comment out HTML lines of code, one at a time, to search for errors:
 * Example
 ```html
 <!DOCTYPE html>
 <html>
 <body>
 <!-- Do not display this at the moment
 <img border="0" src="pic_trulli.jpg" alt="Trulli">
 -->
 </body>
 </html>
 ```

## HTML Colors

HTML colors are specified with predefined color names, or with RGB, HEX, HSL, RGBA, or HSLA values.

### Color Names

In HTML, a color can be specified by using a color name:

 | <h4 style="background-color:Tomato;text-align: center;">Tomato</h4>  | <h4 style="background-color:Orange;text-align: center;">Orange</h4> |
 | :---  |  ---: |
 | <h4 style="background-color:DodgerBlue;text-align: center;">DodgerBlue</h4>       | <h4 style="background-color:MediumSeaGreen;text-align: center;">MediumSeaGreen</h4>     |
 | <h4 style="background-color:Gray;text-align: center;">Gray</h4>      | <h4 style="background-color:SlateBlue;text-align: center;">SlateBlue</h4>        |
 | <h4 style="background-color:Violet;text-align: center;">Violet</h4>       | <h4 style="background-color:LightGray;text-align: center;">LightGray</h4>       |


 * Example:
 ```html
 <!DOCTYPE html>
 <html>
 <body>
   <h1 style="background-color:Tomato;">Tomato</h1>
   <h1 style="background-color:Orange;">Orange</h1>
   <h1 style="background-color:DodgerBlue;">DodgerBlue</h1>
   <h1 style="background-color:MediumSeaGreen;">MediumSeaGreen</h1>
   <h1 style="background-color:Gray;">Gray</h1>
   <h1 style="background-color:SlateBlue;">SlateBlue</h1>
   <h1 style="background-color:Violet;">Violet</h1>
   <h1 style="background-color:LightGray;">LightGray</h1>
 </body>
 </html>
 ```
 * HTML supports [140 standard color names](https://www.w3schools.com/colors/colors_names.asp).

#### Background Color

You can set the background color for HTML elements:

### <h3 style="background-color:DodgerBlue;text-align: center;">Heading 1</h3>

<p style="background-color:Tomato;">This is a paragraph. Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat. Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>

 * Example:
 ```html
 <!DOCTYPE html>
 <html>
 <body>
   <h1 style="background-color:DodgerBlue;">Hello World</h1>
   <p style="background-color:Tomato;">
     Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.
     Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.
   </p>
 </body>
 </html>
 ```
#### Text Color

You can set the color of text:

<h4 style="color:Tomato;">Hello World</h4>

<p style="color:DodgerBlue;">Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>

<p style="color:MediumSeaGreen;">Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>

 * Example
 ```html
 <!DOCTYPE html>
 <html>
 <body>
 <h3 style="color:Tomato;">Hello World</h3>
   <p style="color:DodgerBlue;">Lorem ipsum dolor sit amet, consectetuer adipiscing elit, sed diam nonummy nibh euismod tincidunt ut laoreet dolore magna aliquam erat volutpat.</p>
   <p style="color:MediumSeaGreen;">Ut wisi enim ad minim veniam, quis nostrud exerci tation ullamcorper suscipit lobortis nisl ut aliquip ex ea commodo consequat.</p>
 </body>
 </html>
 ```

#### Border Color

You can set the color of borders:

<h4 style="border:2px solid Tomato;">Hello World</h4>
<h4 style="border:2px solid DodgerBlue;">Hello World</h4>
<h4 style="border:2px solid Violet;">Hello World</h4>

 * Example:
 ```html
 <!DOCTYPE html>
 <html>
 <body>
   <h1 style="border: 2px solid Tomato;">Hello World</h1>
   <h1 style="border: 2px solid DodgerBlue;">Hello World</h1>
   <h1 style="border: 2px solid Violet;">Hello World</h1>
 </body>
 </html>
 ```

#### Color Values

In HTML, colors can also be specified using RGB values, HEX values, HSL values, RGBA values, and HSLA values.
 * The following three `<div>` elements have their background color set with RGB, HEX, and HSL values:

 <h6 style="background-color:rgb(255, 99, 71);text-align: center;color:White;">rgb(255, 99, 71)</h6>
 <h6 style="background-color:#ff6347;text-align: center;color:White;">#ff6347</h6>
 <h6 style="background-color:hsl(9, 100%, 64%);text-align: center;color:White;">hsl(9, 100%, 64%)</h6>

 The following two `<div>` elements have their background color set with RGBA and HSLA values, which adds an Alpha channel to the color (here we have 50% transparency):

 <h6 style="background-color:rgba(255, 99, 71, 0.5);text-align: center;color:White;">rgba(255, 99, 71, 0.5)</h6>
 <h6 style="background-color:hsla(9, 100%, 64%, 0.5);text-align: center;color:White;">hsla(9, 100%, 64%, 0.5)</h6>

 * Example:
 ```html
 <!DOCTYPE html>
 <html>
 <body>
   <p>Same as color name "Tomato":</p>
     <h1 style="background-color:rgb(255, 99, 71);">rgb(255, 99, 71)</h1>
     <h1 style="background-color:#ff6347;">#ff6347</h1>
     <h1 style="background-color:hsl(9, 100%, 64%);">hsl(9, 100%, 64%)</h1>
   <p>Same as color name "Tomato", but 50% transparent:</p>
     <h1 style="background-color:rgba(255, 99, 71, 0.5);">rgba(255, 99, 71, 0.5)</h1>
     <h1 style="background-color:hsla(9, 100%, 64%, 0.5);">hsla(9, 100%, 64%, 0.5)</h1>
   <p>In addition to the predefined color names, colors can be specified using RGB, HEX, HSL, or even transparent colors using RGBA or HSLA color values.</p>
 </body>
 </html>
 ```

#### Learn more about Color Values

You will learn more about [RGB](https://www.w3schools.com/html/html_colors_rgb.asp), [HEX](https://www.w3schools.com/html/html_colors_hex.asp) and [HSL](https://www.w3schools.com/html/html_colors_hsl.asp) in the next chapters.

#### Conclusion
This concludes Part 8 of the Notes on HTML5 Coursework for the Video Course and Tutorial information from W3Schools.com. Please move on to the next document [HTML5-NOTES-PT-9.md](https://github.com/AdamRj-765/W3School-0005/blob/master/COURSE_NOTES/HTML5-NOTES-PT-9.md).


# W3School-0005 - HTML5 NOTES-PT-6


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the [HTML Video Playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB) listed in the project's README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).


## HTML Styles

The HTML `style` attribute is used to add styles to an element, such as color, font, size, and more.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>I am normal</p>
   <p style="color:red;">I am red</p>
   <p style="color:blue;">I am blue</p>
   <p style="font-size:50px;">I am big</p>
 </body>

 </html>
 ```
### The HTML Style Attribute

 Setting the style of an HTML element, can be done with the `style` attribute.
 * The HTML `style` attribute has the following syntax:
 ```html
 <tagname style="property:value;">
 ```
 * The ***property*** is a CSS property. The ***value*** is a CSS value.
 * You will learn more about CSS later in this tutorial.

### Background Color

 The CSS `background-color` property defines the background color for an HTML element.
 * Example #1:
 ```html
 <!DOCTYPE html>
 <html>

 <body style="background-color:powderblue;">
   <h1>This is a heading</h1>
   <p>This is a paragraph.</p>
 </body>

 </html>
 ```

 * Example #2:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <h1 style="background-color:powderblue;">This is a heading</h1>
   <p style="background-color:tomato;">This is a paragraph.</p>
 </body>

 </html>
 ```

### Text Color
 The CSS `color` property defines the text color for an HTML element:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <h1 style="color:blue;">This is a heading</h1>
   <p style="color:red;">This is a paragraph.</p>
 </body>

 </html>
 ```

### Fonts

 The CSS `font-family` property defines the font to be used for an HTML element:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <h1 style="font-family:verdana;">This is a heading</h1>
   <p style="font-family:courier;">This is a paragraph.</p>
 </body>

 </html>
 ```

### Text Size

 The CSS `font-size` property defines the text size for an HTML element:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <h1 style="font-size:300%;">This is a heading</h1>
   <p style="font-size:160%;">This is a paragraph.</p>
 </body>

 </html>
 ```

### Text Alignment

 The CSS `text-align` property defines the horizontal text alignment for an HTML element:
 * Example
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <h1 style="text-align:center;">Centered Heading</h1>
   <p style="text-align:center;">Centered paragraph.</p>
 </body>

 </html>
 ```

### Chapter Summary

 - Use the `style` attribute for styling HTML elements
 - Use `background-color` for background color
 - Use `font-family` for text fonts
 - Use `font-size` for text sizes
 - Use `text-align` for text alignment

## HTML Text Formatting

 HTML contains several elements for defining text with a special meaning.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p><b>This text is bold</b></p>
   <p><i>This text is italic</i></p>
   <p>This is<sub> subscript</sub> and <sup>superscript</sup></p>
 </body>

 </html>
 ```

### HTML Formatting Elements

 Formatting elements were designed to display special types of text:

 - `<b>` - Bold text
 - `<strong>` - Important text
 - `<i>` - Italic text
 - `<em>` - Emphasized text
 - `<mark>` - Marked text
 - `<small>` - Smaller text
 - `<del>` - Deleted text
 - `<ins>` - Inserted text
 - `<sub>` - Subscript text
 - `<sup>` - Superscript text

### HTML `<b>` and `<strong>` Elements

The HTML `<b>` element defines bold text, without any extra importance.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>This text is normal.</p>
   <p><b>This text is bold.</b></p>
 </body>

 </html>
 ```

The HTML `<strong>` element defines text with strong importance. The content inside is typically displayed in bold.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>This text is normal.</p>
   <p><strong>This text is important!</strong></p>
 </body>

 </html>
 ```

### HTML `<i>` and `<em>` Elements

The HTML `<i>` element defines a part of text in an alternate voice or mood. The content inside is typically displayed in italic.
 * **Tip**: The `<i>` tag is often used to indicate a technical term, a phrase from another language, a thought, a ship name, etc.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>This text is normal.</p>
   <p><i>This text is italic.</i></p>
 </body>

 </html>
 ```
The HTML `<em>` element defines emphasized text. The content inside is typically displayed in italic.
 * **Tip**: A screen reader will pronounce the words in `<em>` with an emphasis, using verbal stress.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>This text is normal.</p>
   <p><em>This text is emphasized.</em></p>
 </body>

 </html>
 ```
### HTML `<small>` Element

 The HTML `<small>` element defines smaller text:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>This is some normal text.</p>
   <p><small>This is some smaller text.</small></p>
 </body>

 </html>
 ```

### HTML `<mark>` Element

The HTML `<mark>` element defines text that should be marked or highlighted:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>Do not forget to buy <mark>milk</mark> today.</p>
 </body>

 </html>
 ```

### HTML `<del>` Element

The HTML `<del>` element defines text that has been deleted from a document. Browsers will usually strike a line through deleted text:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>My favorite color is <del>blue</del> red.</p>
 </body>

 </html>
 ```

### HTML `<ins>` Element

The HTML `<ins>` element defines a text that has been inserted into a document. Browsers will usually underline inserted text:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>My favorite color is <del>blue</del> <ins>red</ins>.</p>
 </body>

 </html>
 ```

### HTML `<sub>` Element

The HTML `<sub>` element defines subscript text. Subscript text appears half a character below the normal line, and is sometimes rendered in a smaller font. Subscript text can be used for chemical formulas, like H<sub>2</sub>O:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>This is <sub>subscripted</sub> text.</p>
 </body>

 </html>
 ```

### HTML `<sup>` Element

The HTML `<sup>` element defines superscript text. Superscript text appears half a character above the normal line, and is sometimes rendered in a smaller font. Superscript text can be used for footnotes, like WWW<sup>[1]</sup>:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>This is <sup>superscripted</sup> text.</p>
 </body>
 
 </html>
 ```

 | Tag  | Description |
 | :---        |          ---: |
 | `<b>`       | Defines bold text     |
 | `<em>`      | Defines emphasized text        |
 | `<i>`       | Defines a part of text in an alternate voice or mood       |
 | `<small>`   | Defines smaller text       |
 | `<strong>`  | Defines important text       |
 | `<sub>`     | Defines subscripted text       |
 | `<sup>`     | Defines superscripted text      |
 | `<ins>`     | Defines inserted text       |
 | `<del>`     | Defines deleted text       |
 | `<mark>`    | Defines marked/highlighted text       |


#### Conclusion
This concludes Part 6 of the Notes on HTML5 Coursework for the Video Course and Tutorial information from W3Schools.com. Please move on to the next document [HTML5-NOTES-PT-7.md](https://github.com/AdamRj-765/W3School-0005/blob/master/COURSE_NOTES/HTML5-NOTES-PT-7.md).

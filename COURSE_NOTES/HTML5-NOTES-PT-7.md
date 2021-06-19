
# W3School-0005 - HTML5 NOTES-PT-7


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the [HTML Video Playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB) listed in the project's README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).


## HTML Quotation and Citation Elements

In this chapter we will go through the `<blockquote>`,`<q>`, `<abbr>`, `<address>`, `<cite>`, and `<bdo>` HTML elements.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>
 <body>

   <p>Here is a quote from WWF's website:</p>
   <blockquote cite="http://www.worldwildlife.org/who/index.html">
     For 50 years, WWF has been protecting the future of nature.
     The world's leading conservation organization,
     WWF works in 100 countries and is supported by
     1.2 million members in the United States and
     close to 5 million globally.
   </blockquote>
 </body>

 </html>
 ```
### HTML `<blockquote>` for Quotations

The HTML `<blockquote>` element defines a section that is quoted from another source.
 * Browsers usually indent <blockquote> elements.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>Browsers usually indent blockquote elements.</p>
   <blockquote cite="http://www.worldwildlife.org/who/index.html">
     For nearly 60 years, WWF has been protecting the future of nature. The world's leading conservation organization, WWF works in 100 countries and is supported by more than one million members in the United States and close to five million globally.
   </blockquote>
 </body>

 </html>
 ```

### HTML `<q>` for Short Quotations

The HTML `<q>` tag defines a short quotation.
 * Browsers normally insert quotation marks around the quotation.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>Browsers usually insert quotation marks around the q element.</p>
   <p>WWF's goal is to: <q>Build a future where people live in harmony with nature.</q></p>
 </body>

 </html>
 ```

### HTML `<abbr>` for Abbreviations

The HTML `<abbr>` tag defines an abbreviation or an acronym, like "HTML", "CSS", "Mr.", "Dr.", "ASAP", "ATM".
 * Marking abbreviations can give useful information to browsers, translation systems and search-engines.
 * **Tip**: Use the global title attribute to show the description for the abbreviation/acronym when you mouse over the element.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>The <abbr title="World Health Organization">WHO</abbr> was founded in 1948.</p>
   <p>Marking up abbreviations can give useful information to browsers, translation systems and search-engines.</p>
 </body>

 </html>
 ```
### HTML `<address>` for Contact Information

The HTML `<address>` tag defines the contact information for the author/owner of a document or an article.
 * The contact information can be an email address, URL, physical address, phone number, social media handle, etc.
 * The text in the `<address>` element usually renders in italic, and browsers will always add a line break before and after the `<address>` element.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>The HTML address element defines contact information (author/owner) of a document or article.</p>
   <address>
     Written by John Doe.<br>
     Visit us at:<br>
     Example.com<br>
     Box 564, Disneyland<br>
     USA
   </address>
 </body>

 </html>
 ```
### HTML `<cite>` for Work Title

The HTML `<cite>` tag defines the title of a creative work (e.g. a book, a poem, a song, a movie, a painting, a sculpture, etc.).
 * **Note**: A person's name is not the title of a work.
 * The text in the `<cite>` element usually renders in italic.
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>The HTML cite element defines the title of a work.</p>
   <p>Browsers usually display cite elements in italic.</p>
     <img src="img_the_scream.jpg" width="220" height="277" alt="The Scream">
   <p><cite>The Scream</cite> by Edvard Munch. Painted in 1893.</p>
 </body>

 </html>
 ```

### HTML `<bdo>` for Bi-Directional Override

BDO stands for Bi-Directional Override.
 * The HTML `<bdo>` tag is used to override the current text direction:
 * Example:
 ```html
 <!DOCTYPE html>
 <html>

 <body>
   <p>If your browser supports bi-directional override (bdo), the next line will be written from right to left (rtl):</p>
  <bdo dir="rtl">This line will be written from right to left</bdo>
 </body>
 
 </html>
 ```

### HTML Quotation and Citation Elements


 | Tag  | Description |
 | :---        |          ---: |
 | `<abbr>`       | Defines an abbreviation or acronym     |
 | `<address>`      | Defines contact information for the author/owner of a document        |
 | `<bdo>`       | Defines the text direction       |
 | `<blockquote>`   | Defines a section that is quoted from another source       |
 | `<cite>`  | Defines the title of a work       |
 | `<q>`     | Defines a short inline quotation       |




#### Conclusion
This concludes Part 7 of the Notes on HTML5 Coursework for the Video Course and Tutorial information from W3Schools.com. Please move on to the next document [HTML5-NOTES-PT-8.md](https://github.com/AdamRj-765/W3School-0005/blob/master/COURSE_NOTES/HTML5-NOTES-PT-8.md).

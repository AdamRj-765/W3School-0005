
# W3School-0005 Video Notes Pt 5


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the [HTML Video Playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB) listed in the project's README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).



### HTML Attribute Reference

A complete list of all attributes for each HTML element, is listed in W3School's: [HTML Attribute Reference](https://www.w3schools.com/tags/ref_attributes.asp).


### HTML Headings

HTML headings are titles or subtitles that you want to display on a webpage.
 * Example
 ```html
 <!DOCTYPE html>
 <html lang="en-US">

 <head>
    <meta charset="utf-8" />
    <title>Test Formatting Index</title>
 </head>

 <body>
    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>
 </body>

 </html>
 ```

#### More on HTML Headings

HTML headings are defined with the `<h1>` to `<h6>` tags.
 * Note: Browsers automatically add some white space (a margin) before and after a heading.
 * Headings Are Important
 	* Search engines use the headings to index the structure and content of your web pages.
 	* Users often skim a page by its headings. It is important to use headings to show the document structure.
	* `<h1>` headings should be used for main headings, followed by `<h2>` headings, then the less important `<h3>`, and so on.
	* Note: Use HTML headings for headings only. Don't use headings to make text BIG or bold.
 * Bigger Headings
 	* Each HTML heading has a default size. However, you can specify the size for any heading with the `style` attribute, using the CSS `font-size` property:
	```html
	<h1 style="font-size:60px;">Heading 1</h1>
	```
### HTML Tag Reference

W3Schools' tag reference contains additional information about these tags and their attributes.


 | Left-aligned | Center-aligned | Right-aligned |
 | :---         |     :---:      |          ---: |
 | git status   | git status     | git status    |
 | git diff     | git diff       | git diff      |


 | Tag  | Description |
 | :---         |     :---:      |          ---: |
 | &lsaquo; html &rsaquo;   | Defines the root of an HTML document     |
 | &lsaquo; body &rsaquo;     | Defines the document's body       |
 | &lsaquo; h1 &rsaquo; to &lsaquo; h6 &rsaquo;     | Defines HTML headings       |



 | Tag        | Description |
 | :---         |     :---:      |          ---: |
 | &lsaquo; html &rsaquo;     | 	Defines the root of an HTML document |
 | &lsaquo; body &rsaquo;      | 	Defines the document's body |
 | &lsaquo; h1 &rsaquo; to &lsaquo; h6 &rsaquo; | Defines HTML headings |

```
| Tag                         | Description                            |
| --------------------------- | -------------------------------------- |
| <html>                      | Defines the root of an HTML document   |
| <body>                      | Defines the document's body            |
| <h1> to <h6>                | Defines HTML headings                  |
```

 * For a complete list of all available HTML tags, visit our [HTML Tag Reference](https://www.w3schools.com/tags/default.asp).


### HTML Paragraphs

A paragraph always starts on a new line, and is usually a block of text.
 * HTML Paragraphs - The HTML `<p>` element defines a paragraph.
 * A paragraph always starts on a new line, and browsers automatically add some white space (a margin) before and after a paragraph.
 * Example
 ```html
 <p>This is a paragraph.</p>
 <p>This is another paragraph.</p>
 ```
 * HTML Display - You cannot be sure how HTML will be displayed.
 * Large or small screens, and resized windows will create different results.
 * With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.
 * The browser will automatically remove any extra spaces and lines when the page is displayed:
 * Example:
 ```html
 <p>
 This paragraph
 contains a lot of lines
 in the source code,
 but the browser
 ignores it.
 </p>

 <p>
 This paragraph
 contains         a lot of spaces
 in the source         code,
 but the        browser
 ignores it.
 </p>
 ```

### HTML Horizontal Rules

The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.
 * The `<hr>` element is used to separate content (or define a change) in an HTML page:
 * Example:
 ```html
 <h1>This is heading 1</h1>
 <p>This is some text.</p>
 <hr>
 <h2>This is heading 2</h2>
 <p>This is some other text.</p>
 <hr>
 ```
 * The `<hr>` tag is an empty tag, which means that it has no end tag.

### HTML Line Breaks

The HTML `<br>` element defines a line break.
 * Use <br> if you want a line break (a new line) without starting a new paragraph:
 * Example
 ```html
 <p>This is<br>a paragraph<br>with line breaks.</p>
 ```
 The `<br>` tag is an empty tag, which means that it has no end tag.

### The Poem Problem
This poem will display on a single line:
 ```html
 <p>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</p>
```

#### Solution - The HTML <pre> Element
The HTML `<pre>` element defines preformatted text.
 * The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks:
 ```html
 <pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```
### HTML Tag Reference
W3Schools' tag reference contains additional information about HTML elements and their attributes.
 * For a complete list of all available HTML tags, visit our [HTML Tag Reference](https://www.w3schools.com/tags/default.asp).




#### Conclusion
This concludes Part 3 of the Notes on HTML5 Coursework for the Video Course and information from W3Schools.com. Please move on to the next document [HTML-NOTES-PT-6.md](https://github.com/AdamRj-765/W3School-0005/blob/master/COURSE_NOTES/HTML5-NOTES-PT-6.md).

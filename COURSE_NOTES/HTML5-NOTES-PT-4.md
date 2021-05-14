# W3School-0005 Video Notes Pt 4


## INTRODUCTION

These notes will provide the information compiled and deemed helpful in understanding the information given in both the [HTML Video Playlist](https://www.youtube.com/playlist?list=PLr6-GrHUlVf_ZNmuQSXdS197Oyr1L9sPB) listed in the project's README.md, and from the HTML online tutorials from [W3Schools.com](https://www.w3schools.com/).


28. Summery
	* We learned in the last HTML5-NOTES document ("PT-3") that all *elements* have *attributes*. We also learned about the `<a>` element and it's attribute `href`, and the `<img>` element and one of it's attributes called the `src` attribute. That attributes are always specified in **the start tag**, and that they are defined in the format of the *attribute name*,  then an equal sign (`=`), and then a *value*.
	* We also learned how to use the `href` and the `src` attributes to link to files that are located in these different situations:
		1. **Absolute URLs** which are a full internet URL or web link in the format:

		*protocol* *domain* *folder* *filename*
		 (`https://`)(`omni-solutions-tech.com/`)(`imgs/`)(`image-1.jpg`)
		...as seen here:
		```html
		<img src="https://www.omni-solutions-tech.com/imgs/omni-solutions-banner.jpg">
		```
		2. **Relative URLs** which can handle links to files within the site's file system and that are in a child folder, adjacent folder, or parent folder.
		3. When testing pages on a local file system, you will use a slightly different pathing if you are testing without a domain.

### The width and height Attributes

 The `<img>` tag should also contain the `width` and `height` attributes, which specifies the width and height of the image (in pixels).
 * Example:
 ```html
 <img src="img_girl.jpg" width="500" height="600">
 ```
### The alt Attribute

 The required `alt` attribute for the `<img>` tag specifies an alternate text for an image, if the image for some reason cannot be displayed. This can be due to slow connection, or an error in the `src` attribute, or if the user uses a screen reader.
 * Example:
 ```html
 <img src="img_typo.jpg" alt="Girl with a jacket">
 ```

### The style Attribute

 The `style` attribute is used to add styles to an element, such as color, font, size, and more.
 * Example:
 ```html
 <p style="color:red;">This is a red paragraph.</p>
 ```

### The lang Attribute

 You should always include the `lang` attribute inside the `<html>` tag, to declare the language of the Web page. This is meant to assist search engines and browsers.
 * The following example specifies English as the language:
 ```html
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
 * Country codes can also be added to the language code in the `lang` attribute. So, the first two characters define the language of the HTML page, and the last two characters define the country.
 * The following example specifies English as the language and United States as the country:
 ```html
 <!DOCTYPE html>
 <html lang="en-US">
    <head>
       <meta charset="utf-8"/>
       <title>Index-1 Page </title>
    </head>
    <body>
       <img src="images/image-1.jpg" alt="Omni-Solutions Tech">
    </body>
 </html>
 ```

### The title Attribute

 The `title` attribute defines some extra information about an element.
 * The value of the title attribute will be displayed as a tooltip when you mouse over the element:
 ```html
 <p title="I'm a tooltip">This is a paragraph.</p>
 ```

### We Suggest: Always Use Lowercase Attributes
 The HTML standard does not require lowercase attribute names.
 * The title attribute (and all other attributes) can be written with uppercase or lowercase like **title** or **TITLE**.
 * However, W3C **recommends** lowercase attributes in HTML, and **demands** lowercase attributes for stricter document types like XHTML.

### We Suggest: Always Quote Attribute Values

 The HTML standard does not require quotes around attribute values.
 * However, W3C **recommends** quotes in HTML, and **demands** quotes for stricter document types like XHTML.
 * **Good:**
 ```html
 <a href="https://www.omni-solutions-tech.com/html/">Visit our HTML tutorial</a>
 ```
 * **Bad:**
 ```html
 <a href=https://www.w3schools.com/html/>Visit our HTML tutorial</a>
 ```
 * Sometimes you have to use quotes. This example will not display the title attribute correctly, because it contains a space:
 ```html
 <p title=About W3Schools>
 ```
### Single or Double Quotes?

 Double quotes around attribute values are the most common in HTML, but single quotes can also be used.
 * In some situations, when the attribute value itself contains double quotes, it is necessary to use single quotes:
 ```html
 <p title='John "ShotGun" Nelson'>
 ```
 * Or vice versa:
 ```html
 <p title="John 'ShotGun' Nelson">
 ```

### Chapter Summary

 * All HTML elements can have **attributes**
 * The `href` attribute of `<a>` specifies the URL of the page the link goes to
 * The `src` attribute of `<img>` specifies the path to the image to be displayed
 * The `width` and `height` attributes of `<img>` provide size information for images
 * The `alt` attribute of `<img>` provides an alternate text for an image
 * The `style` attribute is used to add styles to an element, such as color, font, size, and more
 * The `lang` attribute of the `<html>` tag declares the language of the Web page
 * The `title` attribute defines some extra information about an element

#### Conclusion
This concludes Part 3 of the Notes on HTML5 Coursework for the Video Course and information from W3Schools.com. Please move on to the next document [HTML-NOTES-PT-5.md](https://github.com/AdamRj-765/W3School-0005/blob/master/COURSE_NOTES/HTML5-NOTES-PT-5.md).

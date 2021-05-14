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

 	The `<img>` tag should also contain the `width` and `height` attributes, which specifies the width and height of the image (in pixels):
	```html
	<img src="img_girl.jpg" width="500" height="600">

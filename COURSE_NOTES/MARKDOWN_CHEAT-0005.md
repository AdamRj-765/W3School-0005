
# My Markdown Cheat Sheet #0005
























## Testing area

*this is in italic*  and _so is this_

**this is in bold**  and __so is this__

***this is bold and italic***  and ___so is this___


A carriage return
makes a line break.

Two carriage returns make a new paragraph.


> Use it if you're quoting a person, a song or whatever.

> You can use *italic* or lists inside them also.
And just like with other paragraphs,
all of these lines are still
part of the blockquote, even without the > character in front.

To end the blockquote, just put a blank line before the following
paragraph.





First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell



First Header                       |
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell



[[download_button]]

[[gittip_button username=foo]]

[[members]]

[[project_screenshots]]


Regular content<sup>superscript content</sup> Regular Content <sub>subscript content</sub>

<s>this is strike through text</s>

Here's a simple footnote,[^1] and here's a longer one.[^bignote]

[^1]: This is the first footnote.

[^bignote]: Here's one with multiple paragraphs and code.


    Indent paragraphs to include them in the footnote.

    `{ my code }`

    Add as many paragraphs as you like.



### My Great Heading {#custom-id}

<h3 id="custom-id">My Great Heading</h3>



First Term
: This is the definition of the first term.

Second Term
: This is one definition of the second term.
: This is another definition of the second term.


<dl>
  <dt>First Term</dt>
  <dd>This is the definition of the first term.</dd>
  <dt>Second Term</dt>
  <dd>This is one definition of the second term. </dd>
  <dd>This is another definition of the second term.</dd>
</dl>



- [x] Write the press release
- [ ] Update the website
- [ ] Contact the media


`http://www.example.com`




### Links

[Omni-Solutions Tech](https://omni-solutions-tech.com "We Partner With You")

You can also put the [link URL][1] below the current paragraph
like [this][2].

   [1]: http://url
   [2]: http://another.url "A funky title"


Or you can use a [shortcut][] reference, which links the text
"shortcut" to the link named "[shortcut]" on the next paragraph.

[shortcut]: http://goes/with/the/link/name/text



[MyWikiPage]       # Wiki - name of wiki page
[#123]             # Tracker - ticket number
[r10721]           # SVN - revision number
[3b9d48]           # Git & Mercurial - first 6 characters of revision hash
[2012/02/my-post]  # Blog - post slug, including YYYY/MM/ prefix
[a6d38f98]         # Discussion Thread - thread id
[a6d38f98#42f8]    # Discussion Post - thread_id#post_id


[bugs:#1]
[features:#1]



<canvas id="myCanvas" width="200" height="100"></canvas>

<canvas id="myCanvas" width="200" height="100" style="border:1px solid #000000;"></canvas>




### ASCII charts

* Here is a project bones for a website:

```
W3School-0005/
├── .git/
├── COURSE_NOTES/
|   ├── HTML5-NOTES-PT-1.md
|   ├── HTML5-NOTES-PT-2.md
|   └── MARKDOWN_CHEAT.md
├── public_html/
|   └── index.html
├── public_html_templates/
|   ├── default_w3c_index.html
|   ├── default_w3c_index-0005.html
|   ├── default_w3c_index-0010.html
|   ├── default_w3c_index-0015.html
|   ├── default_w3c_index-0020.html
|   ├── default_w3c_index-0025.html
|   ├── default_w3c_refreshes_index-0030.html
|   └── default_w3c_responsive_index-0005.html
├── .gitattributes
├── .gitignore
├── LICENSE.md
└── README.md
```



<pre>
.
+-- _config.yml
+-- _drafts
|   +-- begin-with-the-crazy-ideas.textile
|   +-- on-simplicity-in-technology.markdown
+-- _includes
|   +-- footer.html
|   +-- header.html
+-- _layouts
|   +-- default.html
|   +-- post.html
+-- _posts
|   +-- 2007-10-29-why-every-programmer-should-play-nethack.textile
|   +-- 2009-04-26-barcamp-boston-4-roundup.textile
+-- _data
|   +-- members.yml
+-- _site
+-- index.html
</pre>



```
project
│   README.md
│   file001.txt    
│
└───folder1
│   │   file011.txt
│   │   file012.txt
│   │
│   └───subfolder1
│       │   file111.txt
│       │   file112.txt
│       │   ...
│   
└───folder2
    │   file021.txt
    │   file022.txt
```


📦quakehunter
 ┣ 📂client
 ┣ 📂node_modules
 ┣ 📂server
 ┃ ┗ 📜index.js
 ┣ 📜.gitignore
 ┣ 📜package-lock.json
 ┗ 📜package.json




.. code::
.
|-- ContentStore
|   |-- de-DE
|   |   |-- art.mshc
|   |   |-- artnoloc.mshc
|   |   |-- clientserver.mshc
|   |   |-- noarm.mshc
|   |   |-- resources.mshc
|   |   `-- windowsclient.mshc
|   `-- en-US
|       |-- art.mshc
|       |-- artnoloc.mshc
|       |-- clientserver.mshc
|       |-- noarm.mshc
|       |-- resources.mshc
|       `-- windowsclient.mshc
`-- IndexStore
    |-- de-DE
    |   |-- art.mshi
    |   |-- artnoloc.mshi
    |   |-- clientserver.mshi
    |   |-- noarm.mshi
    |   |-- resources.mshi
    |   `-- windowsclient.mshi
    `-- en-US
        |-- art.mshi
        |-- artnoloc.mshi
        |-- clientserver.mshi
        |-- noarm.mshi
        |-- resources.mshi
        `-- windowsclient.mshi


root
├── dir1
│   └── file1
└── dir2
    └── file2

```
<pre>
.
&#8866; README.md
&#8866; docs
&#8866; e2e
&#8866; karma.conf.js
&#8866; node_modules
&#8866; package.json
&#8866; protractor.conf.js
&#8866; src
&#8866; tsconfig.json
&#8985; tslint.json
</pre>

```




* [HERE](https://stackoverflow.com/questions/19699059/representing-directory-file-structure-in-markdown-syntax) is an excelent document on this subject of file system trees.






* Here is a chart sowing a diagram of basic webpage:

```
┌────────────────────────────────────────────────────────────────────────────────────────────────────────────┐
| <html>                                                                                                     |
|  ┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐  |
|  | <head>                                                                                               |  |
|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
|  |  | <title>Page title</title>                                                                      |  |  |
|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
|  | </head>                                                                                              |  |
|  └──────────────────────────────────────────────────────────────────────────────────────────────────────┘  |
|  ┌──────────────────────────────────────────────────────────────────────────────────────────────────────┐  |
|  | <body>                                                                                               |  |
|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
|  |  | <h1> This is the H1 Heading </h1>                                                              |  |  |
|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
|  |  | <p> This is H1's paragraph </p>                                                                |  |  |
|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
|  |  | <h2> This is the H2 Heading </h2>                                                              |  |  |
|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
|  |  ┌────────────────────────────────────────────────────────────────────────────────────────────────┐  |  |
|  |  | <p> This is H2's paragraph </p>                                                                |  |  |
|  |  └────────────────────────────────────────────────────────────────────────────────────────────────┘  |  |
|  | </body>                                                                                              |  |
|  └──────────────────────────────────────────────────────────────────────────────────────────────────────┘  |
| </html>                                                                                                    |
└────────────────────────────────────────────────────────────────────────────────────────────────────────────┘
```

Here is

<script src="https://cdn.jsdelivr.net/npm/mermaid/dist/mermaid.min.js"></script>



* Links on the same page:
* And [HERE](https://stackoverflow.com/questions/2822089/how-to-link-to-part-of-the-same-document-in-markdown?rq=1) for more on links

* Github automatically parses anchor tags out of your headers. So you can do the following:

```markdown
[Custom foo description](#foo)

# Foo
```
* In the above case, the Foo header has generated an anchor tag with the name foo

Note: just one # for all heading sizes, no space between # and anchor name, anchor tag names must be lowercase, and delimited by dashes if multi-word.

```markdown
[click on this link](#my-multi-word-header)

### My Multi Word Header
```

* Experimenting, I found a solution using <div…/> but an obvious solution is to place your own anchor point in the page wherever you like, thus:
```html
<a name="abcde">
```
 *line you want to link to*
```html
</a>
```
Then link to this part of the page with:

```markdown
[link text](#abcde)
```








## Main Markdown Links

* GitHub Flavored Markdown
	* [GitHub Flavored Markup](https://docs.github.com/en/github/writing-on-github) (a.k.a. GFM)
	* [GFM Markdown Editor](https://jbt.github.io/markdown-editor/)
	* [The R Markdown Cookbook](https://bookdown.org/yihui/rmarkdown-cookbook/)

* Markdown Syntax
	* [Stack Overflow](https://stackoverflow.com/search?q=markdown)
	* [Markdown Guide](https://www.markdownguide.org/)

* Extended Markdown
	* [Extended Markdown](https://www.markdownguide.org/extended-syntax/)




* Wiki Markdown
[Schematics](https://sourceforge.net/p/schematics/wiki/markdown_syntax/)




* Diagrams in Markdown
	* HTML Canvas is the best I have found besides the ASCII code examples above:
	[HTML Canvas on W3Schools](https://www.w3schools.com/graphics/canvas_intro.asp)

* Mermaid Suggestions
	* [unknoown](https://cloudinary.com/blog/create_markdown_diagrams_and_charts_for_developers_and_architects)
	* [Mermaid Gist](https://mermaid-js.github.io/mermaid/#/)

* [Sketchboard](https://sketchboard.io/blog/2014/03/06/github-sketchboard.html)

* SVG based Images
	* [Embed a diagram in GitHub markdown](https://drawio.freshdesk.com/support/solutions/articles/16000042371-embed-a-diagram-in-github-markdown)
* The Markdown Cookbook Diagrams
	* [Chpt 4.15 Markdown Diagrams](https://bookdown.org/yihui/rmarkdown-cookbook/diagrams.html)
* Typora Markdown Diagrams
	* [Markdown Diagrams](https://support.typora.io/Draw-Diagrams-With-Markdown/)
* Engineering Diagrams With KiCAD
	* [KiCAD Diagrams](https://github.com/MalphasWats/hawk/blob/master/articles/creating-the-schematic.markdown)
* Diagrams in Documentation (Markdown Guide)
	* [Diagrams in Documentation (Markdown Guide)](https://medium.com/technical-writing-is-easy/diagrams-in-documentation-markdown-guide-4e78419e8d2f)


https://drawio.freshdesk.com/support/solutions/articles/16000042371-how-to-use-draw-io-in-github-markdown-
https://gist.github.com/rodneyrehm/40e7946c0cff68a31cea
https://gist.github.com/blackcater/1701e845a963216541591106c1bb9d3b
https://dev.to/markhopson/help-architecture-diagrams-for-github-readme-md-1pl7
https://github.community/t/feature-request-support-mermaid-markdown-graph-diagrams-in-md-files/1922/116
https://dev.to/rahulmanojcet/how-to-draw-flowchart-diagrams-in-markdown-using-mermaid-2f18
https://stackoverflow.com/questions/15155778/superscript-in-markdown-github-flavored?rq=1


https://stackoverflow.com/questions/34836305/how-do-i-make-a-flowchart-using-markdown-on-my-github-blog

### Repositories That Handle Markdown

* Unknown links

	* [GitHub Unknown](https://gist.github.com/rodneyrehm/40e7946c0cff68a31cea)





https://gist.github.com/search?q=markdown.md

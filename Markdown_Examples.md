Markdown Examples

Bold 	**text** 	Ctrl/⌘ + B
Emphasize 	*text* 	Ctrl/⌘ + I
Strike-through 	~~text~~ 	Ctrl + Alt + U
Link 	[title](http://) 	Ctrl/⌘ + K
Inline Code 	`code` 	Ctrl/⌘ + Shift + K
Image 	![alt](http://) 	Ctrl/⌘ + Shift + I
List 	* item 	Ctrl + L
Blockquote 	> quote 	Ctrl + Q
H1 	# Heading 	 
H2 	## Heading 	Ctrl/⌘ + H
H3 	### Heading 	Ctrl/⌘ + H (x2)
Headers

Headers are set using a hash before the title. The number of hashes before the title text will determine the depth of the header. Header depths are from 1-6

    H1 : # Header 1
    H2 : ## Header 2
    H3 : ### Header 3
    H4 : #### Header 4
    H5 : ##### Header 5
    H6 : ###### Header 6

Text Styling

    Links : [Title](URL)
    Bold : **Bold**
    Italicize : *Italics*
    Strike-through : ~~text~~
    Highlight : ==text==
    Paragraphs : Line space between paragraphs
    Line break : Add two spaces to the end of the line
    Lists : * an asterisk for every new list item.
    Quotes : > Quote
    Inline Code : `alert('Hello World');`
    Horizontal Rule (HR) : --------

Images

You can drag and drop images (.png, .gif, .jpg) from your Desktop over the editor to include them with your post, or alternatively click the image icon from the editor toolbar to use a standard image upload popup. 

Adding Alt Text
To add alt text to your image, all you need to do is place the text in-between the square brackets, e.g;![This is a alt text]().

Hyperlinking Images
To hyperlink your image, wrap the image markdown in the markdown for creating a link. E.g. [![Image Alt Text](/path/to/image)](path/to/linked/page)

Be sure read How to Add an Image to Your Post for a full instruction on image handling with your Ghost blog.
Footnotes

Footnotes can be added to the body of your text using placeholders like this: [^1] or [^note] coupled with the note text at the end of the document. For example:


Here is a footnote reference,[^1] and another.[^longnote]

 

Then at the end of your post:


[^1]: Here is the footnote.

[^longnote]: Here's one with multiple blocks.

    Subsequent paragraphs are indented to show that they
belong to the previous footnote.

 

Alternatively you can use inline rather than numbered or named footnotes:

Here is an inline note.^[Inlines notes are easier to write, since you don't have to pick an identifier and move down to type the note.]
Writing Code

Inline code can be added using single back-ticks E.g. `alert('Hello World')`.

For code blocks, Ghost supports both standard markdown code blocks and the syntax from GitHub Flavored Markdown (GFM). Standard markdown works by indenting code lines with 4 spaces:

    <header>
        <h1>{{title}}</h1>
    </header>

GFM uses triple back-ticks ```

```
<header>
    <h1>{{title}}</h1>
</header>
```

Examples

Link Markdown Example

This is a paragraph that contains a [link to ghost](http://ghost.org).

List Markdown Example

This paragraph contains a list of items.

* Item 1
* Item 2
* Item three

Quote Markdown Example

This paragraph has a quote

> That is pulled out like this

from the text my post.
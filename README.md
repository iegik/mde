WYGIWYS Right IT Editor
=====================
This is a simplest formatted text editor ever! Everybody knows, that nowdays readers such as iReaver, Kindle and some of Apple products can convert mess html pages (blogs/newslaters) to fine-readable text with smooth styles. What We want to do is give to people simplest editor for formating text in correct way. All styling will be addited automaticaly. You can also include your own theme for editor. As example, in iPhone notes looks like real exercise book.
The best article is that other peoples without this editor also can edit this files, but only in durty way (inline editing), becouse in output always will be text. 

P.S.: All images can be putted as base64 ebbeded content only inside .html (.mht/.mhtml) files.

Supported file types/formats:
------------------------------------------
For me, BB, HTML, Textile, Latex and Markdown - it`s all looks the same. We chosed the Markdown for the general format, becouse it seamplest of both above.
* .txt .md (.markdown) (.tt) .textile .tex (.latex) .bb .html .mht (.mhtml)
* .zip .tar .bz .rar .7z archive export plugins for grouping files with external images and/or styles?
  * filename_files/
  * filename.[format]
* .wri .rtf .doc .docx .odt .pdf import/export plugins?

Links
--------
* maybe helps in development for Markdown part:
  * Markdown Python library: http://pypi.python.org/pypi/Markdown
  * Markdown Perl test: http://six.pairlist.net/pipermail/markdown-discuss/2004-December/000909.html
* HTML and CSS: http://www.w3.org/standards/webdesign/htmlcss
* HTML5: http://www.w3.org/TR/2010/WD-html5-20101019/
* embeded CSS styles:
  * OOCSS: content.css
  * Blueprint: typography.css
  * YUI: text.css, reset.css
* Compass: http://compass-style.org/

UI design
--------------
Simple taskbar for application (html):

<pre> &New | &Save | style (Title <h&3>, &Paragraph <р> | SubTitle <h&4>, Section <h&5>, SubSection <h&6> | Heading 1 <h&1>, Heading 2 <h&2> ) | &Bold <strоng> | Italic <еm> | Link <а> (&h;&u) | &Strike <strikе> | &Right <р style="text-align:right"> | Center <р style="text-align:center"> | &Left <р style="text-align:left"> | Numbering <оl>, Bu&llets <uI> | Block&quote <blockquote></pre>

* "|" - delimiter
* "&" - Short key for action "&New - Ctrl+N"

[[http://img833.imageshack.us/img833/5511/wysiwygtoolbar.png]]

Formatting
---------------

HTML:
```html
<h1>Heading 1</h1>
...
<h6>Heading 6</h6>-
<strike>stroketrought</strike>
<a href="http://example.com">link</a>
<em>Italic</em>
<strong>Bold<strong>
<p>Paragraph</p>
<blockquote>Blockquote</blockquote>
<ol><li>Numbered 1</li><li>Numbered 2</li></ol>
<ul><li>Bullet 1</li><li>Bullet 2</li></ul>
<table><tr><td>cell 1</td><td>cell 2</td></tr></table>
```

For Markdown also have "brackets":
```text
=Heading 1=
...
======Heading 6======
-stroketrought-
http://example.com:link
/Italic/
*Bold*
Paragraph
> Blockquote
# Numbered
* Bullet
| cell 1 | cell 2 |
```

WANTED! Python or other opensource programmer
=====================================

Couse I`m new in Gtk and desktop application proggramming at all - You need me, to do that job.

I replace Underline with Anchor/Link because all we can mark - well mark with "Strong/Bold" and only links must be underlined

TODO:
----------
comments or notes for special word, like references

License
-----------
MIT, CC-BY
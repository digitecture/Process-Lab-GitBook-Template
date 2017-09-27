# Insert Images
![](images/overview/PCP-CurrentPractice.gif)
*Figure 1: Design teams construct ad hoc design spaces*

# Comment Out Text

This text will print \(Look at the code to see the markdown structure that makes this non-print text\).

[comment]: <> (This text will not print)

# Tables

| First Header | Second Header |
| --- | --- |
| Content Cell | Content Cell |
| Content Cell | Content Cell |

# Footnote

Text prior to footnote reference.[^2]

# Links

This is [an example](http://example.com/ "Title") inline link with a title.

[This link](http://example.net/) has no title attribute.

# Lists

1. First ordered list item
2. Another item
   ⋅⋅\* Unordered sub-list.
3. Actual numbers don't matter, just that it's a number
   ⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces \(at least one, but we'll use three here to also align the raw Markdown\).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅  
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅  
⋅⋅⋅\(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.\)

* Unordered list can use asterisks
* Or minuses
* Or pluses

# Code Blocks

Inline `code` has `back-ticks around` it.

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

# Block Quotes

> Blockquotes are very handy in email to emulate reply text.  
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can _put_ **Markdown** into a blockquote.

# Cover

GitBook Documentation  
Cover  
To make your book more elegant on GitBook, you can specify a cover.

A cover is specified by a cover.jpg file, a cover\_small.jpg can also exist as a smaller version of the cover. The cover should be a JPEG file.

Best Sizes

Big    Small  
File    cover.jpg    cover\_small.jpg  
Size\(in pixels\)    1800x2360    200x262  
Autocover

A GitBook plugin \(autocover\) can also be used to generate a cover file for you, or just generate the cover\_small.jpg from your big cover. This plugin is added by default on hosted books.

Read more about autocover.

Guidelines

A good cover respects the following guidelines:

No border  
Clearly visible book title  
Any important text should be visible in the small version

[^2]: Comment to include in footnote.


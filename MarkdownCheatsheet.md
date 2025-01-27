# HEADERS
There are two ways to define header:
1. Way one: Biggest Possible Header
   =
2. # Way two: Biggest Possible Header
3. ## Header
4. ### Header
5. #### Header
6. ##### Header
7. ###### Smallest Possible Header
---
# Separating Paragraphs
1. Using `*`, three or more
***
2. Using `_`, three or more
___
3. Using `-`, three or more
---
4. Using `---` immediately after a single line test , gets an header, so either leave a blank line or put it after multiple lines
   ---
# FootNote
This is a Single line footnote [^1].

This is multiline footnote. [^2].

[^1]: Reference for single line footnote.

[^2]: To add line breaks within a footnote, prefix new lines with 2 spaces.

This is third line. References are automatically at end the document.
---
# Lists
## Unordered list
Can start with single `-`, `*` or `+`.

Use them to create nested bullet points.

1. Way one
- First list item
  - first nested list item
    - second nested list item
2. Way two
- First list item
  * first nested list item
     + second nested list item
3. Way three
+ First list item
  - first nested list item
     * second nested list item
4. etc....
# Ordered list
Start by numbering 1. ,2. 3. ....
1. item 1
2. item 2
3. item 3
4. etc....
1) Other way
2) etc....
---
# Checkboxes
- [x] `- [x]` for checked box
- [ ] `- [ ]` for unchecked box
  - [ ] add to 2 spaces in front for nesting
      - [ ] second nesting of checkbox
---
# Block Quotes
> Use `>` for nesting

> To crete new block quote add a empty line
>
>> This creates nested block quote
>>> This creates second nested block quote

    > We can't indent with more than 3 spaces
# To create Note, Tip, Important, Caution Blocks
> [!NOTE]

> [!NOTE] Custom Text
> This way we can add custom name for this type of block. `[!NOTE] custom text`. Similarly for other blocks.

> [!TIP]

> [!IMPORTANT]

> [!WARNING]

> [!CAUTION]

#  Source code
There are two ways:
 1. inline code like this: `*Text1* **Text2**"`
 2. fenced code blocks (use ` ``` ` or `~~~` as delimiters):
``` any text here is ignored
*Hello* **world!**
```

# Links
- You can insert links in text like [this](/example.md)

- You may add a [title](https://examlesite.com/page1 "Markdown CheatSheet") to your link (You will see Markdown CheatSheet when hover over link text)

- If your link contains spaces you have to write the [link](<http://example.com/a space>) between `<>`

- You can use spaces and markup inside the [link **text**](https://examplesite.com/page1)

- You may also write directly the link: <https://examplesite.com/page1>

- It will work also for email addresses: <email@example.com> (you may write valid email links also using [mailto](mailto:email@example.com) as protocol)


# Linking heading

## Sample Section

## This'll be a _Helpful_ Section About the Greek Letter Θ!
A heading containing characters not allowed in fragments, UTF-8 characters, two consecutive spaces between the first and second words, and formatting.

## This heading is not unique in the file

TEXT 1

## This heading is not unique in the file

TEXT 2

# Links to the example headings above

Link to the sample section: [Link Text](#sample-section).

Link to the helpful section: [Link Text](#thisll--be-a-helpful-section-about-the-greek-letter-Θ).

Link to the first non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file).

Link to the second non-unique section: [Link Text](#this-heading-is-not-unique-in-the-file-1).

# Text Modification
### For Bold
1. Use `**text**` for **bold**
2. Use `__text__` for __bold__

### For Italic
1. Use `*text*` for *italic*
2. Use `_text_` for _italic_

To force line break use `\` or two spaces at end of the line, like this

### For Strike through
Use `~~ ~~` for ~~Mistaken text~~ .

### All Bold and Italic
Use `*** ***` for ***bold and italic***.

### For Subscript
Use `<sub> </sub>`\
ex: This is a <sub>subscript</sub> text.

### For Superscript
Use `<sup> </sup>`\
This is a <sup>superscript</sup> text.

### For Underline
Use `<ins> </ins>`\
This is an <ins>underlined</ins> text.

# Adding Images
Syntax for images is like the syntax for links, but with a `!` before:
1. Way One
![C++ Logo (this will be shown if image fails to load)](c++logo.png "C++ logo (this will show when hovering over image)")
1. Way Two
![](Images/rustLogo.png)

# Escaping
If you have to write something that would result in a Markdown valid syntax, you can escape the first character of your expression (you may also escape any other punctuation character) with a `\`

\*not emphasized\*

\<br/> not a tag

\[not a link](/foo)

\`not code`

1\. not a list

\* not a list

\# not a header

\[foo]: /url "not a reference"

You may also escape the backslash itself \\*like this*
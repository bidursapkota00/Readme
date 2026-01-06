# Markdown Syntax Guide

![Bidur Sapkota](https://www.bidursapkota.com.np/images/gravatar.webp "Bidur Sapkota - Developer")&nbsp;[Bidur Sapkota](https://www.bidursapkota.com.np/)

Markdown is a lightweight markup language that allows you to format text using simple syntax. This guide covers the essential Markdown elements you'll use most frequently.

![Markdown Syntax Guide by Bidur Sapkota](/1-markdown-post-1200.webp "Markdown Syntax Complete Guide - Blog by Bidur Sapkota")

## Table of content

1. [Add Headings](#add-headings)
2. [Text Formatting](#text-formatting)
3. [Lists](#lists)
4. [Links and Images](#links-and-images)
5. [Code](#code)
6. [Blockquotes](#blockquotes)
7. [Tables](#tables)
8. [Horizontal Lines](#horizontal-lines)
9. [Line Breaks](#line-breaks)
10. [Escape Character](#escape-character)
11. [HTML in Markdown](#html-in-markdown)
12. [Creating Table of Content](#creating-table-of-content)

---

## Add Headings

Use hash symbols (#) to create headers. The number of hashes determines the header level:

```markdown
# Header 1 (Largest)

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6 (Smallest)
```

#### Output:

# Header 1 (Largest)

## Header 2

### Header 3

#### Header 4

##### Header 5

###### Header 6 (Smallest)

---

---

---

## Text Formatting

### Bold and Italic

```markdown
**Bold text**
_Italic text_
**_Bold and italic_**
```

#### Output:

**Bold text**  
_Italic text_  
**_Bold and italic_**

---

### Strikethrough

```markdown
~~Strikethrough text~~
```

#### Output:

~~Strikethrough text~~

---

---

---

## Lists

### Unordered Lists

Use dashes (`-`), asterisks (`*`)

```markdown
- Item 1
- Item 2
  - Nested item
  - Another nested item
- Item 3

* Item 4
```

#### Output:

- Item 1
- Item 2
  - Nested item
  - Another nested item
- Item 3

* Item 4

---

### Ordered Lists

Use numbers followed by period and space:

```markdown
1. First item
2. Second item
   1. Nested numbered item
   2. Another nested item
3. Third item
```

#### Output:

1. First item
2. Second item
   1. Nested numbered item
   2. Another nested item
3. Third item

---

---

---

## Links and Images

### Links

Create links using square brackets for text and parentheses for URL:

```markdown
[Link text](https://example.com)
[Link text](https://example.com "Optional title")

<!-- Example -->

[Portfolio Link](https://www.bidursapkota.com.np/)
```

#### Output:

[Portfolio Link](https://www.bidursapkota.com.np/)

---

### Images

Similar to links but with an exclamation mark at the beginning:

```markdown
![Alt text](image-url.jpg)
![Alt text](image-url.jpg "Optional title")

<!-- Example -->

![Profile Picture](/profile.webp)
```

#### Output:

![Profile Picture](/profile.webp)

---

---

---

## Code

### Inline Code

Use single backticks for inline code

```markdown
`inlilne code`

<!-- Example -->

Add internal JavaScript using `<script>` tag
```

#### Output:

Add internal JavaScript using `<script>` tag

---

### Code Blocks

Use triple backticks for code blocks:

````markdown
```javascript
function add(a, b) {
  return a + b;
}
```
````

#### Output:

```javascript
function add(a, b) {
  return a + b;
}
```

---

---

---

## Blockquotes

Use the greater than symbol (>) for blockquotes:

```markdown
> This is a blockquote.
> It can span multiple lines.
>
> > This is a nested blockquote.
```

#### Output:

> This is a blockquote.
> It can span multiple lines.
>
> > This is a nested blockquote.

---

---

---

## Tables

Create tables using pipes (|) and dashes (-):

```text
| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 4   | Cell 5   |
```

#### Output:

| Header 1 | Header 2 |
| -------- | -------- |
| Cell 1   | Cell 2   |
| Cell 4   | Cell 5   |

---

---

### Table Alignment

Use colons (`:`) to align columns:

```text
| Left-aligned |
| :----------- |
| Left         |
```

#### Output:

| Left-aligned |
| :----------- |
| Left         |

---

```text
| Center-aligned |
| :------------: |
|     Center     |
```

#### Output:

| Center-aligned |
| :------------: |
|     Center     |

---

```text
| Right-aligned |
| ------------: |
|         Right |
```

#### Output:

| Right-aligned |
| ------------: |
|         Right |

---

---

---

## Horizontal Lines

Create horizontal lines using three dashes

```text

---

```

#### Output:

---

<br>
<br>

---

---

---

## Line Breaks

- Single line break: End a line with two spaces
- Paragraph break: Leave a blank line between paragraphs
- you can use html `<br>` tag as well

```markdown
paragraph 1
<br>
paragraph 2

paragraph 3
paragraph 4

<!-- without two space in end -->

**Bold text**
_Italic text_

<!-- with two space in end -->

**Bold text**  
_Italic text_
```

#### Output:

paragraph 1
<br>
paragraph 2

paragraph 3
paragraph 4

**Bold text**
_Italic text_

**Bold text**  
_Italic text_

---

---

---

## Escape Character

Use backslash (`\`) to escape special characters:

```markdown
\_This will not be italic\_  
\# This will not be a header
```

#### Output:

\_This will not be italic\_  
\# This will not be a header

---

---

---

## HTML in Markdown

You can use HTML tags within Markdown when needed:

```markdown
This is <mark>highlighted text</mark>.  
<br> This creates a line break.
```

#### Output:

This is <mark>highlighted text</mark>.  
<br>This creates a line break.

---

---

---

## Creating Table of Content

- Every heading text is converted to in-page navigation link using following rules
  > - all heading text is converted to lowercase letters
  > - remove all special characters
  > - replace space by hyphen (`-`)

```markdown
## Table of content

1. [HTML, CSS & Js](#html-css--js)

### HTML, CSS & Js

<!-- all letters to lowercase -->
<!-- removed special characters & and , -->
<!-- replaced space by hyphen -->
```

#### Output:

## Table of content

1. [HTML, CSS & Js](#html-css--js)

### HTML, CSS & Js

---

---

---

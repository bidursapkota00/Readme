# Markdown Syntax Guide

Markdown is a lightweight markup language that allows you to format text using simple syntax. This guide covers the essential Markdown elements you'll use most frequently.

## Headers

Use hash symbols (#) to create headers. The number of hashes determines the header level:

```markdown
# Header 1 (Largest)
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6 (Smallest)
```

## Text Formatting

### Bold and Italic

- **Bold text**: Use double asterisks `**bold**` or double underscores `__bold__`
- *Italic text*: Use single asterisks `*italic*` or single underscores `_italic_`
- ***Bold and italic***: Use triple asterisks `***bold italic***`

### Strikethrough

~~Strikethrough text~~ using double tildes: `~~strikethrough~~`

## Lists

### Unordered Lists

Use dashes (-), asterisks (*), or plus signs (+):

```markdown
- Item 1
- Item 2
  - Nested item
  - Another nested item
- Item 3
```

### Ordered Lists

Use numbers followed by periods:

```markdown
1. First item
2. Second item
   1. Nested numbered item
   2. Another nested item
3. Third item
```

## Links and Images

### Links

Create links using square brackets for text and parentheses for URL:

```markdown
[Link text](https://example.com)
[Link with title](https://example.com "Optional title")
```

### Images

Similar to links but with an exclamation mark at the beginning:

```markdown
![Alt text](image-url.jpg)
![Alt text](image-url.jpg "Optional title")
```

## Code

### Inline Code

Use single backticks for `inline code`: `` `code` ``

### Code Blocks

Use triple backticks for code blocks:

````markdown
```
Basic code block
```

```python
# Code block with syntax highlighting
def hello_world():
    print("Hello, World!")
```
````

## Blockquotes

Use the greater than symbol (>) for blockquotes:

```markdown
> This is a blockquote.
> It can span multiple lines.
>
> > This is a nested blockquote.
```

Result:
> This is a blockquote.
> It can span multiple lines.
>
> > This is a nested blockquote.

## Tables

Create tables using pipes (|) and dashes (-):

```markdown
| Header 1 | Header 2 | Header 3 |
|----------|----------|----------|
| Cell 1   | Cell 2   | Cell 3   |
| Cell 4   | Cell 5   | Cell 6   |
```

### Table Alignment

Use colons (:) to align columns:

```markdown
| Left-aligned | Center-aligned | Right-aligned |
|:-------------|:--------------:|--------------:|
| Left         | Center         | Right         |
```

## Horizontal Rules

Create horizontal lines using three or more dashes, asterisks, or underscores:

```markdown
---
***
___
```

## Line Breaks

- Single line break: End a line with two spaces  
- Paragraph break: Leave a blank line between paragraphs

## Escape Characters

Use backslash (\) to escape special characters:

```markdown
\*This will not be italic\*
\# This will not be a header
```

## HTML in Markdown

You can use HTML tags within Markdown when needed:

```markdown
This is <mark>highlighted text</mark>.
<br>
This creates a line break.
```

## Common Combinations

### Task Lists

```markdown
- [x] Completed task
- [ ] Incomplete task
- [ ] Another incomplete task
```

### Definition Lists

```markdown
Term 1
: Definition 1

Term 2
: Definition 2a
: Definition 2b
```
Result:  

Term 1  
: Definition 1

Term 2  
: Definition 2a  
: Definition 2b

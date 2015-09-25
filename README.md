# codeX Style Guide

Voice, tone, and markdown style guide.
For more consistent and readable code and content.

## Language

* Talk about the coder, using the second person: "Next you will be installing Git."
* Say "on the server" instead of "on the backend."

Placeholder variables are written in all caps, with no spaces inside angle brackets, like: `<USERNAME>`.

### Technical terms

Explain commands immediately after they're used, including any options.

Some common terms and our preferred capitalisation:

* HTML
* CSS
* JavaScript
* jQuery
* AJAX
* Git
* GitHub
* Node (or Node.js)
* SQL
* MySQL
* phpMyAdmin

## Markdown formatting

### Headers

* ATX style
* One space after hash
* Surrounded by a blank line
* No trailing punctuation
* Increment one level at a time


#### Example

```markdown
# Heading 1

Some context text.

## The next heading
```

### Content

* Don't use bare URLs: always use descriptive link text
* Inline code snippets use a single backtick
* Fenced code blocks are surrounded by blank lines and have a language specified
* Emphasis markers, code elements, and link text have no spaces inside
* Code or file names are enclosed by backticks
* Lists
    * are surrounded by a blank line
    * start at the beginning of the line
    * are indented with 4 spaces
    * have spaces after list markers
* Unordered lists use asterisks
* Tables
    * Use `---` for table header dividers
    * [Markdown tables for non-techies](http://www.tablesgenerator.com/markdown_tables)  

#### Examples

```markdown
Check out [project codeX](http://www.projectcodex.co/).
```

```markdown
Change directories using `cd`.
```

```markdown
    ```javascript
    console.log("Hello, world!");
    ```
```

```markdown
Put your code into `hello.js`.
```

```markdown
Web pages are made of:

* HTML
    * Structured Content
* CSS
    * Structured Content
* JavaScript
    * Presentation
```

```markdown
| What | For |
| --- | --- | --- |
| HTML | Structured Content |
| CSS | Presentation |
| JavaScript | Behaviour |
```

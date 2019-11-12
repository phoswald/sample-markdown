# Basic Features

# Heading

The standard format for headings uses a single hash as prefix.

## Sub-heading

The standard format for sub-headings uses two hashes as prefixes.

Heading
=======

The second format for headings uses double dashes on the next line.

Sub-heading
-----------

The second format for sub-headings uses dashes on the next line.

### Sub-sub-headings

Paragraphs are separated
by a blank line.

Two spaces at the end of a line  
produces a line break. Unfortunately they are usually not visible in text editors.

Text can have the attributes _italic_, *italic again*, 
__bold__, **bold again**, or `monospace`.

Horizontal rule is defined by three dashes:

---

Bullet list (using asteriks):

  * apples
  * oranges
  * pears

Bullet list (using dashes):

  - apples
  - oranges
  - pears
      - sub
      - sub

Numbered list:

  1. lather
  2. rinse
  3. repeat
       1. sub
       2. sub

An [example link](http://example.com).

An image ![Image](https://www.google.com/favicon.ico "alternative text")

Source code can be indented using four spaces.

    #!/bin/sh
    echo 'Hello, world!'

> Markdown uses email-style > characters for blockquoting.

Markdown uses backslahses (\\) to escape \*, \{ , \# and more.

# Extensions

A __line break__ can also\
be produced by a __backslash__\
at the end of the line.\
This works in GitHub, VS Code, marked and dillinger, but __not__ in Eclipse, markdownlivepreview or showdownjs.

__Fenced code blocks__ offer an alternative syntax without indentiation. 
They work in GitHub, VS Code, Eclipse, marked, dillinger and showdownjs, but __not__ markdownlivepreview (incorrect layout).

```
#!/bin/sh
echo 'Hello, world!'
```

__Tables__ are an extension defined by GitHub Flavored Markdown. 
They also work in VS Code, marked, dillinger and showdownjs, but __not__ in Eclipse or markdownlivepreview.
If you add two spaces after each row, the layout is readable even if tables are not actually recognized.

xx | yy | zz  
---|----|---  
a | b | c  
1 | 2 | 3  

Inline <u><abbr title="Hypertext Markup Language">HTML</abbr></u> works in Eclipse, VS Code, marked and showdownjs, but __not__ in GitHub, markdownlivepreview and dillinger.

# Corner Cases

## Lists and paragraphs

Lists immediately following a paragraph work in GitHub, VS Code, Eclipse, marked, dillinger and showdownjs, but __not__ in markdownlivepreview. Remember that a paragraph should always be surrounded by empty lines.
- apples
- oranges

## Lists and code blocks

Code blocks following a list are ambigous. Code is recognized in dillinger, which is probably wrong.

  - apples
  - oranges

    code
    block

This can be fixed by using a paragraph before the code block or by using fenced code blocks.

  - apples
  - oranges

.

    code
    block

  - apples
  - oranges

```
code
block
```

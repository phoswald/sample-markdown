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

Inline <u><abbr title="Hypertext Markup Language">HTML</abbr></u> is supported by Eclipse and VS Code.

# Extensions

A line break can also be produced by a backslash \
at the end of the line.
They also work in GitHub, VS Code and dillinger.io, 
but **not** in Eclipse, markdownlivepreview.com or showdownjs.

Tables are an extension defined by GitHub Flavored Markdown. 
They also work in VS Code, dillinger.io and showdownjs, 
but **not** in Eclipse or markdownlivepreview.com.
If you add two spaces after each row, the layout is readable even if tables are not actually recognized.

xx | yy | zz  
-- | -- | --  
a | b | c  
1 | 2 | 3  

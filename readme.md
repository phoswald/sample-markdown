# sample-markdown

Showcases and tooling for [Markdown](https://en.wikipedia.org/wiki/Markdown)
(see [Cheat Sheet](https://www.markdownguide.org/cheat-sheet/))

## Showcase

Examples are [right here](sample.md).

## IDEs

- Visual Studio Code: Built-in editor for *.md files, also supports tables, 
  press Ctrl+Shift+V or Ctrl+K V for preview
- Eclipse: Built-in editor for *.md file, does not support tables.

## Online Services

- [github.com](https://github.com/phoswald/sample-markdown): Automatically renders *.md files. GitHub supports extensions called GitHub Flavoured Markdown (see [Cheat Sheet](https://guides.github.com/pdfs/markdown-cheatsheet-online.pdf)), which include tables, strikethrough, autolinks and task lists.
- [markdownlivepreview.com](https://markdownlivepreview.com/): Online editor with live preview, does not support tables. 
- [dillinger.io](https://dillinger.io/): Online editor with live preview, also supports tables.
- [demo.showdownjs.com](http://demo.showdownjs.com/): Online editor with live preview, many customizable flags.

## Libaries and Tools

- [showdownjs](https://github.com/showdownjs/showdown): Javascript Markdown to HTML converter, can be used client side (in the browser) or server side (with NodeJS).

### Showdown.js

    $ cd showdown-page
    $ npm init -y
    $ npm install webpack webpack-cli webpack-dev-server --save-dev
    $ npm run start:dev

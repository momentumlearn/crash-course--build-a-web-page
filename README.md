# Crash Course: Build a Web Page

## To run the slides

This slide deck uses three tools to build it: pandoc, devd, and modd. To install on OS X:

```
brew install pandoc devd modd
```

Once installed, run `modd` to serve the slides. Changes to `slides.md` will be automatically compiled into `index.html`. The slides will be available at http://127.0.0.1:8000.

## Topics

* What is a web page?
    * HTML - the content to show
    * CSS - how to style the content
    * JavaScript - code to make the page interactive
* HTML
    * Tree structure
    * &lt;tag&gt; syntax
    * Tags
        * DOCTYPE
        * html
        * head
        * title
        * body
        * headers
        * p
        * strong and em
        * section
        * ul, ol, and li
        * article
        * div
    * Tag attributes
        * a
        * img
        * link
        * span
        * The class attribute
* CSS
    * Selecting a tag
    * Selecting a class
    * syntax
    * Units: px, %, em, rem
    * CSS properties
        * Text and fonts
            * color
                * named colors, hex colors
            * font-size
            * font-family
            * font-weight
            * text-decoration
            * text-align
        * Blocks
            * background-color
            * padding
            * margin
            * border-color
            * border-width
            * border-style
            * border-radius
            * width

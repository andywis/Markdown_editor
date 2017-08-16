# Markdown_Editor.html - An in-browser Markdown editor

This editor is based on the [showdown](https://github.com/showdownjs/showdown)
library.

## Dependencies
There is only one dependency: the **showdown.js** library, which you can obtain
from the link above. The simplest way is to just download dist/showdown.min.js.
There is probably a _proper_ way to do it is to use Bower, but simply copying
the file is about as easy as it gets.

Everything else is inside the HTML file, to make it dead easy to use :-)

## Setting up
1. Clone or download the HTML file from this repo.
1. **mkdir showdown-1.6.4/dist**  (or, on Windows, **mkdir showdown-1.6.4\dist**)
1. Copy showdown-min.js into the newly created folder


## Usage
1. Double-click the Markdown_Editor.html to load it into your browser.
1. Paste the Markdown into the type-in box at the top of the page
1. Hit "Convert"
1. See how your marked-down document looks in the box below the buttons.

## Keyboard shortcuts.
There aren't any, but press tab to move between the type-in field and the 
buttons. Focus handlers put focus back onto the type-in box when the page
loads and after clicking "Clear"

## Bugs
* I think there's a CSS error if you try to do in-line code elements.

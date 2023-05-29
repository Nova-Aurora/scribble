# Scribble
A basic HTML5 + JavaScript drawing program designed to show off some features of HTML and JS to a friend

Source code entry is `index.html` inside the docs directory.

This is designed to be simple, and so there are a number of improvements left to the reader.

* It continues to draw after you release the cursor. Try using the `mouseleave` event to disable drawing when the canvas is left
* The canvas is fixed size. Try looking at the `canvasElement.width` and `canvasElement.height` attributes, and `ctx.getImageData()`, as well as `ctx.drawImage()`
* It looks bad. This is up to personal preference, but look at css to your preference if you want.

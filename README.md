# lavender-editorial-doodle
An interactive magazine page where text flows around lavender stars, a photo, flowers and your own doodles.
interactive magazine-style page where the body text flows around whatever you place or draw on it.
Features
White 16:9 page, black serif type, large "streams of influence" headline
Four dense columns of body text, laid out on a canvas with no DOM text measurement
Lavender stars stay fixed, and the text wraps around them
Your profile photo, two lavender flowers and your own coloured doodles can be dragged, and the text reflows around them live
Draw mode with a 9-colour palette, brush size, Undo and Clear doodles
Upload your own photo from your gallery with the Your photo button
How to use
Open the page.
Move mode: drag the photo, flowers or doodles.
Draw mode: pick a colour and write or draw anywhere, then switch to Move to drag it.
Tap Your photo to put your picture in the circle.
The photo resets when the page is refreshed.
Files
Only one file is needed: `index.html`. All styling and code are inside it.
Run it
Locally: double-click `index.html`.
On GitHub Pages: Settings, Pages, Deploy from a branch, `main` and `/ (root)`.
Tech
Plain HTML, CSS and JavaScript on a single canvas. Words are measured once with `canvas.measureText`, then placed line by line around the open space left by the shapes.

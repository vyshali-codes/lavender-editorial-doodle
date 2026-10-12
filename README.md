# lavender-editorial-doodle
An interactive magazine page where text flows around lavender stars, a photo, flowers and your own doodles.
# Lavender Editorial Doodle

An interactive, magazine-style editorial canvas where text flows naturally around photos, flowers, stars, and hand-drawn doodles. Create your own artistic layout by dragging elements, uploading a profile photo, and drawing with colourful brushes.

## Features

* **Editorial Layout:** White 16:9 canvas with black serif typography and a large "Streams of Influence" headline.
* **Four-Column Text Layout:** Dense body text arranged across four columns.
* **Dynamic Text Wrapping:** Text automatically rearranges around movable objects in real time.
* **Fixed Lavender Stars:** Decorative stars remain in place while the text flows around them.
* **Draggable Elements:** Move your profile photo, two lavender flowers, and custom doodles anywhere on the canvas.
* **Drawing Mode:** Draw or write freely using a 9-colour palette.
* **Brush Controls:** Adjust brush size to create different drawing styles.
* **Undo & Clear:** Undo your latest doodle or clear your drawings.
* **Upload Your Photo:** Use the **Your Photo** button to upload an image from your device gallery.
* **Interactive Modes:** Switch between Move mode and Draw mode whenever you like.

## Preview

The project features a minimalist editorial aesthetic with lavender decorations, serif typography, and interactive canvas elements.

## How to Use

1. Open the page in your browser.
2. Select **Move mode** to drag the photo, flowers, or doodles.
3. Select **Draw mode** to draw or write anywhere on the canvas.
4. Choose a colour from the 9-colour palette.
5. Adjust the brush size to your preference.
6. Use **Undo** to remove your latest drawing or **Clear** to clear all doodles.
7. Click **Your Photo** to upload your own picture into the circular photo frame.
8. Switch back to Move mode to reposition movable elements.

**Note:** The uploaded photo resets when the page is refreshed.

## Technologies Used

* HTML5
* CSS3
* JavaScript
* HTML Canvas API

## Project Structure

```text
Lavender-Editorial-Doodle/
│
└── index.html
```

The entire project is contained in a single HTML file, including the styling and JavaScript logic.

## How to Run

### Run Locally

1. Download or clone this repository.
2. Open the project folder.
3. Double-click `index.html`.
4. The page will open in your default web browser.

No installation or additional dependencies are required.

### Run with GitHub Pages

1. Open your GitHub repository.
2. Navigate to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Choose the `main` branch.
5. Select `/ (root)` as the folder.
6. Click **Save**.
7. Wait for GitHub Pages to deploy your website.

Your project will then be accessible through its GitHub Pages URL.

## How It Works

The application uses a single HTML canvas to render the editorial layout and interactive elements.

* Text is measured using the Canvas API's `measureText()` method.
* Words are positioned line by line across four columns.
* The layout calculates available space around objects and adjusts the text accordingly.
* Movable elements trigger live text reflow when repositioned.
* Mouse interactions support dragging and freehand drawing.
* The drawing tools provide colour selection, brush-size adjustment, undo, and clear functionality.

Unlike conventional HTML layouts, the text is rendered directly onto the canvas without relying on DOM-based text measurement.

## Future Enhancements

* Save and restore custom layouts.
* Export the completed canvas as a PNG image.
* Add more decorative elements and font styles.
* Support touch gestures for mobile devices.
* Allow users to customise the headline and body text.

## License

This project is available for learning, personal use, and further development. Add a specific open-source license if you intend to distribute it under particular terms.

---

**Created with HTML, CSS, JavaScript, and a touch of lavender creativity.**

# Customizing tool for Online Meeting Background Images

This project allows users to create customized Teams background images by overlaying text on a selected background image. Users can input their name and title, select a background from a dropdown list, toggle text colors, and save the result as a PNG file.

## Features

- **Dynamic Text Input**: Add a name and title to overlay on the background image.
- **Background Selection**: Choose from a list of predefined background images.
- **Text Color Toggle**: Switch text color between white and black using a toggle switch.
- **Image Export**: Save the customized image as a PNG file.

## Technologies Used

- HTML
- CSS
- JavaScript
- ASPX for backend integration

## How to Use

1. Open the project in a browser that supports HTML5.
2. Use the text fields to input your name and title.
3. Select a background image from the dropdown menu.
4. Toggle the text color using the switch.
5. Click `Update Text` to preview the changes on the canvas.
6. Save the customized image by clicking `Save Image`.

## File Structure

- **`index.html`**: Main file containing the HTML and JavaScript for rendering the UI and functionality.
- **`Backgrounds/`**: Folder containing the predefined background images.
- **`README.md`**: Instructions and documentation for the project.

## Key Functions

### `drawCanvas()`
Draws the selected background and overlays the input text with the chosen color.

### `updateCanvas()`
Refreshes the canvas when text inputs or other settings are changed.

### `updateBackground()`
Loads the selected background image into the canvas.

### `toggleTextColor()`
Switches the text color between white and black based on the toggle switch state.

### `saveImage()`
Generates a PNG file from the canvas and prompts the user to download it.

## Future Enhancements

- Support for uploading custom background images.
- Additional text styling options (e.g., font size, alignment).
- Improved mobile responsiveness.

## License

This project is open-source and available under the MIT License.


# Background Changer Project

This project is a simple JavaScript application that allows users to change the background of an HTML document's `body` element using three different background options.

## How to Use

1. Clone this repository to your local machine or download the source code as a ZIP file.
2. Open the `index.html` file in your web browser.
3. Click on the buttons to change the background of the page.
   - Button 1: Change to Background 1
   - Button 2: Change to Background 2
   - Button 3: Change to Background 3

## How It Works

The JavaScript code in the `script.js` file defines a function `changeBackground(number)` that takes a parameter `number`. This function changes the background of the `body` element based on the provided `number`.

1. When the function is called with a valid number ('1', '2', or '3'), it checks if the current background class is already applied to the `body`. If it matches, it does not apply the new background again to avoid flickering.
2. If the `number` is not one of the specified cases (1, 2, or 3), the function doesn't do anything.

## Examples

To change the background, click on one of the buttons on the web page.

## Contributions

Contributions to this project are welcome! If you find any issues or have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

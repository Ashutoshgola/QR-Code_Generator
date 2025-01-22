# QR-Code_Generator
A simple Node.js-based QR code generator. Takes a user-provided URL, generates a QR code image, and saves the input URL in a text file.
Uses the **`inquirer`** npm package to get user input via the terminal.
- Converts the user-provided URL into a QR code using the **`qr-image`** npm package.
- Saves the entered URL into a `.txt` file using Node.js's native `fs` module.

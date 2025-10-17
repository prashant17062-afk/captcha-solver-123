# Captcha Solver Application

This is a simple, single-file responsive HTML application designed to simulate a CAPTCHA solver interface. It utilizes Tailwind CSS for styling and includes basic JavaScript to handle image loading and CAPTCHA validation.

## Features

*   **Responsive Design:** Built with Tailwind CSS, ensuring a consistent experience across various screen sizes.
*   **Dynamic Image Loading:** Displays a CAPTCHA image, defaulting to `sample.png` or loading an image from a URL parameter (`?url=https://example.com/image.png`).
*   **CAPTCHA Input:** Provides an input field for users to enter the CAPTCHA text.
*   **Client-Side Validation:** Simulates CAPTCHA validation (for the provided sample image "ADUR3").

## Getting Started

To run this application, simply open the `index.html` file in your web browser. Ensure that `sample.png` is located in the same directory as `index.html` if you wish to use the default image.

### Dynamic Image Loading

You can specify a CAPTCHA image URL by appending a `?url=` query parameter to the `index.html` file.

**Example:**
`index.html?url=https://example.com/path/to/your/captcha.png`

## Project Structure

*   `index.html`: The main single-file HTML application.
*   `sample.png`: The default CAPTCHA image used when no URL parameter is provided.
*   `README.md`: This file, providing an overview of the project.
*   `LICENSE`: Contains the MIT License details.

## Technologies Used

*   HTML5
*   Tailwind CSS (CDN)
*   JavaScript

## License

This project is open-source and available under the MIT License. See the `LICENSE` file for more details.
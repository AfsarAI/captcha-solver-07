# CAPTCHA Solver Web Application

This is a simple, single-page web application designed to demonstrate a basic CAPTCHA verification process. It features a dark theme, responsive design, and uses Tailwind CSS for styling.

## Features

-   **CAPTCHA Display**: Shows a static CAPTCHA image (`image.png`).
-   **User Input**: An input field to enter the CAPTCHA text.
-   **Verification Logic**: A 'Verify' button to check if the entered text matches the correct CAPTCHA value.
-   **Success/Failure Feedback**: Displays clear messages indicating the verification outcome.
-   **Responsive Design**: Adapts to different screen sizes.
-   **Dark Theme**: Utilizes a dark color scheme for a modern look.

## Technologies Used

-   **HTML5**: Structure of the web page.
-   **Tailwind CSS**: Utility-first CSS framework for rapid styling.
-   **JavaScript**: For handling user interaction and CAPTCHA verification logic.

## Setup and Running Instructions

This project is a single-file frontend application, making it extremely easy to set up and run.

1.  **Save the files**: Save the `index.html` content into a file named `index.html`.
2.  **Place the CAPTCHA image**: Ensure that the CAPTCHA image file (named `image.png`) is in the same directory as your `index.html` file. The provided `image.png` is based on the sample `V4XBG` image.
3.  **Open in Browser**: Simply open the `index.html` file using any modern web browser (e.g., Chrome, Firefox, Edge, Safari).

    ```bash
    # Example using a file path
    open index.html
    ```

    Alternatively, you can use a local web server (like `live-server` for Node.js or Python's `http.server`) to serve the files, though it's not strictly necessary for this static page.

    **Using Python's built-in HTTP server:**
    ```bash
    cd /path/to/your/project
    python -m http.server
    ```
    Then navigate to `http://localhost:8000` in your browser.

## Usage

1.  Observe the CAPTCHA image displayed on the page.
2.  Enter the text you see in the CAPTCHA image into the input field.
    *   The correct CAPTCHA for the provided image is `V4XBG`.
3.  Click the 'Verify' button or press `Enter`.
4.  A message will appear below the button indicating whether your entry was 'Verification Successful!' (green) or 'Verification Failed.' (red).

## Customization

-   **CAPTCHA Image**: To change the CAPTCHA image, replace `image.png` with your desired image, ensuring it's named `image.png` and placed in the same directory as `index.html`.
-   **Correct CAPTCHA Value**: Modify the `correctCaptcha` variable in the JavaScript section of `index.html` to match your new image's text.
    ```javascript
    const correctCaptcha = 'YOUR_NEW_CAPTCHA_TEXT';
    ```
-   **Styling**: Adjust Tailwind CSS classes directly within `index.html` to customize the appearance.

Enjoy using this simple CAPTCHA solver demo!

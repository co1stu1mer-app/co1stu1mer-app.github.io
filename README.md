# co1stu1mer-app.github.io (blank)

This is a basic static HTML starter project you can build on however you like. No need to save. While you develop your site, your changes will happen 🪄 immediately in the preview window. You can upload assets like images or audio in `assets` to the left. The rest is up to you and your imagination.

## What's in this project?

← `README.md`: That's this file, where you can tell people what your cool website does and how you built it.

← `index.html`: This is the main HTML page for your site.

← `style.css`: CSS files add styling rules to your content.

← `dynamic_proxy.js`:  files add styling rules to your content.

 ← `ip.js`: files add styling rules to your content.
 
 ← `node anti_blokir.js`: files add styling rules to your content.
 
 ← `proxy.py`: CSS files add styling rules to your content.
 
 ← `proxy_worker.js`: CSS files add styling rules to your content.

← `script.js`: If you're feeling fancy you can add interactivity to your site with JavaScript.

![Glitch](https://cdn.glitch.com/a9975ea6-8949-4bab-addb-8a95021dc2da%2FLogo_Color.svg?v=1602781328576)

## You built this with Glitch!

[Glitch](https://glitch.com) is a friendly community where millions of people come together to build web apps and websites.

- Need more help? [Check out our Help Center](https://help.glitch.com/) for answers to any common questions.
- Ready to make it official? [Become a paid Glitch member](https://glitch.com/pricing) to boost your app with private sharing, more storage and memory, domains and more.


![Screenshot](https://s6.uupload.ir/files/screen_shot_1402-10-29_at_23.07.43_q9n9.png)

### Overview

This project implements a simple key logging system to capture user input and display it in a textarea. The system provides comprehensive information to the user during input, allowing tracking of entered words whenever the space or Enter key is pressed. The primary components include HTML for the user interface, CSS for styling, and JavaScript for the key logging functionality.

### Project Structure

- **HTML File (`index.html`):**
  - Defines the structure of the web page.
  - Includes an input field for password entry, a "Check" button, and a textarea for displaying the log.
  - Links to the CSS file for styling and the JavaScript file for functionality.

- **CSS File (`style.css`):**
  - Provides styling for the user interface, creating an aesthetically pleasing layout.
  - Applies a dark theme to the entire page.

- **JavaScript File (`script.js`):**
  - Implements the key logging functionality using two main functions:
    - `startLogger(inputSelector, inputType = 'id', callback)`: Initializes the key logger for a specified input element.
      - Parameters:
        - `inputSelector`: The selector for the input element (ID or class).
        - `inputType='id'`: The type of input selector. Defaults to 'id'. Accepts values 'id' or 'class'.
        - `callback`: The callback function to handle the received information.
      - Throws an error if the input type is incorrect.
    - `updateTextArea(arr)`: Updates a textarea element with an array of strings.
      - Parameters:
        - `arr`: An array of strings to be displayed in the textarea.
      - Updates the content of the textarea identified by the 'logTextarea' ID with the joined strings from the provided array.
      - Additionally, adjusts the textarea height to a fixed value (15em).

  - Utilizes event listeners to track input changes, blur events, and Enter key presses.

### How to Use

1. Open `index.html` in a web browser.

2. Enter text into the password input field.

3. Press the space key or Enter key to capture entered words.

4. The captured words will be displayed in the textarea.

### Additional Information

- The project includes a screenshot (`screen_shot_1402-10-29_at_23.07.43.png`) for reference.

- Ensure to provide valid `inputSelector` and a `callback` function when using the `startLogger` function.

- This project is intended for educational purposes and showcases a basic key logging implementation.

Feel free to explore, modify, and use the code as needed! If you have any questions or suggestions, please reach out.

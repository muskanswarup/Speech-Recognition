# Speech to Text Converter

This is a simple web-based Speech to Text Converter using JavaScript. It leverages the Web Speech API to convert spoken language into written text, demonstrating basic speech recognition functionality in web applications.

## Features

1. Start and stop speech recognition with a button click.
2. Display the recognized text in real-time.
3. Show the confidence level of the recognized text.
4. Accessibility features for screen readers.

## Demo
[Live Demo](https://speech-recognition-taupe-eta.vercel.app/)

## Usage

1. Click the "Speech To Text" button.
2. Start speaking, and your speech will be converted to text.
3. The recognized text and its confidence level will be displayed on the screen.

## Code Overview

### HTML
The HTML file sets up the basic structure of the application, including a button to start the speech recognition and a section to display the recognized text.

### CSS
The CSS file styles the application, making it visually appealing and user-friendly.

### JavaScript
The JavaScript file contains the main logic for the speech recognition functionality. It initializes the SpeechRecognition object, handles the events for starting, processing, and ending the speech recognition, and updates the DOM with the results.

## Accessibility
The button includes aria-label for screen readers.
The output and action elements use aria-live to provide real-time updates to screen readers.

## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Deployment
To deploy this project, you can use any static site hosting service like GitHub Pages, Vercel, Netlify, etc.

## Acknowledgments
This project uses the [Web Speech API](https://developer.mozilla.org/en-US/docs/Web/API/Web_Speech_API) for speech recognition.

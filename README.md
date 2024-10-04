# PRO-FIT - Fit Pulse Tracker

## Overview

PRO-FIT is a web application designed to help users track their workout durations and discover their fitness habits. By entering workout durations separated by commas, users can easily find out the longest duration they have worked out. The application is designed with a clean and responsive user interface to enhance user experience.

## Features

- **User Input**: Users can enter multiple workout durations separated by commas.
- **Duration Calculation**: The app calculates and displays the longest workout duration from the user's input.


## How to Use

1. **Enter Workout Durations**: In the input field labeled "Workout Duration", enter your workout durations separated by commas (e.g., `30, 45, 60`).
2. **Check the Duration**: Click the "Check" button to calculate the longest workout duration.
3. **View Result**: The longest duration will be displayed below the button.


## Technologies Used

- **HTML**: For the structure and layout of the web application.
- **CSS**: For styling the application and making it visually appealing.
- **JavaScript**: For interactive features and dynamic content processing.

## JavaScript Functionality
### Event Handling
- The application listens for a click event on the "Check" button. When clicked, it triggers the function to process the input.

### Input Validation
- The application checks if the input is empty and prompts the user if so.
- It verifies that all entries are valid numbers using the `isNaN()` function.

### Data Processing
- The input string is split into an array of numbers using the `split()` function.
- Each substring is converted to a number using `map()`.
- The application iterates through the array to find the largest number using a simple loop.

### Result Display
- The result is displayed on the page, providing immediate feedback to the user.

## Built-in Functions Used

- **`addEventListener()`**: Attaches an event handler to the button.
- **`getElementById()`**: Accesses HTML elements for interaction.
- **`alert()`**: Notifies users of input errors.
- **`value`**: Retrieves user input from the input field.
- **`split()`**: Breaks the input string into an array.
- **`map()`**: Converts string elements into numbers.
- **`some()`**: Checks for any non-numeric entries in the array.
- **`isNaN()`**: Validates that inputs are actual numbers.
- **`textContent`**: Updates the result displayed on the page.


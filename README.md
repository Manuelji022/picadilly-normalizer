# picadilly-normalizer
Picadilly CSS reset

Normalizer.css is a custom CSS file designed to provide a consistent baseline for styling HTML elements across different browsers. It includes rules to normalize the default styles and improve the overall appearance and usability of web pages.

## Features

- **Box Sizing Rules**: Ensures consistent `box-sizing` across all elements.
  ```css
  *,
  *::before,
  *::after {
    box-sizing: border-box;
  }

- **Prevent Font Size Inflation**: Disables text size adjustments in various browsers.
  ```css
    html {
    -moz-text-size-adjust: none;
    -webkit-text-size-adjust: none;
    text-size-adjust: none;
    }
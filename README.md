# basic-calculator

## Overview
A simple calculator application using HTML, CSS, and JavaScript. It performs basic arithmetic operations and includes functionalities like percentage calculation, clearing the input, and deleting the last entry.


## Features
- **Arithmetic Operations**: Addition, subtraction, multiplication, division.
- **Percentage Calculation**: `%` button.
- **Clear Input**: `AC` button.
- **Delete Last Entry**: `DEL` button.
- **Responsive Design**: Adapts to different screen sizes.

## File Structure
```
calculator/
├── index.html
├── style.css
├── script.js
└── README.md
```

## Usage
- Click buttons to input numbers and operations.
- Use `AC` to clear the display.
- Use `DEL` to delete the last digit.
- Use `=` to calculate the result.

## Implementation Details

### HTML
- `div.container`: Main container.
- `input.display`: Shows input and results.
- `div.buttons`: Contains buttons with `data-value` attributes.

### CSS
- Centered layout using Flexbox.
- Modern look with padding, border-radius, and box-shadow.
- Buttons styled with padding, background color, and active state feedback.

### JavaScript
- Selectors for display and buttons.
- Event listeners for button clicks.
- `calculate(btnValue)`: Manages button logic and updates display.

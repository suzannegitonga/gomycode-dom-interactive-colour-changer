# DOM Color Changer

A simple and interactive web application that demonstrates DOM manipulation by allowing users to change the background color of a box with a single click.

## Features

- **Random Color Generation**: Generates a random hexadecimal color code each time the button is clicked
- **Interactive UI**: Clean, centered interface with a prominent color box and button
- **Responsive Design**: Works on different screen sizes with centered layout
- **Hover Effects**: Button includes hover styling for better user experience

## Technologies Used

- **HTML5**: Structure and semantic markup
- **CSS3**: Styling and layout
- **Vanilla JavaScript**: DOM manipulation and event handling

## How to Use

1. Clone or download the project files
2. Open `index.html` in any modern web browser
3. Click the "Change Color" button to see the color box change to a random color

## Project Structure

```
dom-color-changer/
├── index.html      # Main HTML file with the application structure
├── style.css       # CSS styles for layout and appearance
└── script.js       # JavaScript for color changing functionality
```

## Code Overview

### HTML (`index.html`)
- Contains the basic structure with a container, heading, color box div, and button
- Links to the CSS and JavaScript files

### CSS (`style.css`)
- Styles the body with a light background
- Centers the content using flexbox-like centering
- Defines the appearance of the color box (200x200px with border)
- Styles the button with padding, colors, and hover effects

### JavaScript (`script.js`)
- Waits for the DOM to load before executing
- Selects the color box and button elements
- Defines a `getRandomColor()` function that generates random hex colors
- Adds a click event listener to the button that changes the box's background color

## Browser Compatibility

Works in all modern browsers that support:
- ES6 arrow functions and `addEventListener`
- CSS3 properties like `border-radius`

## Future Enhancements

Potential improvements could include:
- Color history to show previously generated colors
- Color picker for manual color selection
- Animation transitions when changing colors
- Save favorite colors to local storage

## License

This project is open source and available under the [MIT License](https://opensource.org/licenses/MIT).
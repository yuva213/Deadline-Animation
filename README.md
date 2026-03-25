# Deadline Animation

An interactive web-based SVG animation illustrating a countdown to a "deadline". This project creatively visualizes the pressure of a looming deadline with a designer working feverishly as time (rendered as an approaching fire/death animation) ticks down.

## Features
- **Dynamic CSS and SVG Animation**: Uses keyframes and CSS transforms to animate a designer working, with a progressively shrinking time window represented by a red bar.
- **JavaScript Timing**: Uses jQuery to synchronize text countdowns (e.g., "Deadline 7 days") with the visual animation.
- **Looping Mechanism**: The animation and countdown naturally cycle every 20 seconds.
- **Responsive SVG Elements**: Leverages scalable vector graphics for crisp elements like the designer, death character, flames, and timer trail. 

## Technology Stack
- **HTML5**: For structural elements and inline SVGs.
- **CSS3**: For complex responsive layouts, masks, and CSS animation durations.
- **JavaScript (jQuery)**: For dynamically updating the DOM elements, managing timeouts for animation speeds, and handling the countdown timer.

## How to Run

1. Clone or download this repository.
2. Ensure you have the following files in the same directory:
   - `index.html`
   - `style.css`
   - `script.js`
3. Open `index.html` in any modern web browser to view the animation locally. No server or build process is required.

## Customization

You can easily adjust the duration of the animation and the number of days directly in the `script.js` file:
```javascript
var animationTime = 20, // Total duration of one cycle in seconds
    days = 7;           // Total number of deadline days
```

## Credits
Based on a concept by @coding.pixel. Uses Google Fonts (Oswald) and jQuery 2.2.4.

# Reacting to a Mouse Click — Event Delegation Demo

**Name:** Asante Mbaya  
**Topic:** Reacting to a Mouse Click

## About This Demo

When a user clicks inside a web page, the browser fires a click event. Instead of attaching a separate event listener to every individual element on the page, **event delegation** works by placing a single listener on a parent container and using the `event.target` property to identify exactly which child element was clicked. This approach is more efficient, scales automatically to elements added dynamically, and keeps the code clean. This demo illustrates the concept through a "Pop the Bubbles" game: one listener on the game area handles all interactions, spawning a new bubble when empty space is clicked, and popping an existing bubble when one is clicked directly.

## How to Run

1. Download or clone this repository
2. Open the `index.html` file in any web browser (Chrome, Firefox, Edge, etc.)
3. No installation, server, or internet connection required, it runs entirely in the browser

This project creates "GlassMorph Pricing Cards" using HTML, CSS, and JavaScript, featuring a glassmorphism design with a hover-tilt effect.

## Features

  * **Glassmorphism Design:** Modern, frosted glass effect for the pricing cards.
  * **Responsive Layout:** Cards are arranged in a flexible container for various screen sizes.
  * **Hover Tilt Effect:** Interactive 3D tilt effect on card hover, powered by Vanilla-Tilt.js.
  * **Dynamic Content Display:** Card content slides up and becomes visible on hover.

## Technologies Used

  * **HTML5:** Structure of the pricing cards and page layout.
  * **CSS3:** Styling, including glassmorphism effects, gradients, and responsive design.
  * **JavaScript:** Implements the hover tilt effect using the Vanilla-Tilt.js library.

## Setup Instructions

1.  **Clone the Repository (if applicable) or Download Files:**
    If this project is part of a Git repository, clone it using:

    ```bash
    git clone https://github.com/alizamir25/Glassmorphism-Cards
    ```

    Otherwise, ensure you have `index.html`, `style.css`, and `main.js` in the same directory.

2.  **Open `index.html`:**
    Simply open the `index.html` file in your web browser. The page will load with the styled pricing cards.

## File Structure

  * `index.html`: The main HTML file containing the structure of the pricing cards.
  * `style.css`: The CSS file responsible for the visual styling, including the glassmorphism effect and layout.
  * `main.js`: The JavaScript file that initializes the Vanilla-Tilt.js library for the hover effect.

## Usage

Hover over the pricing cards to see the tilt effect and the content animate into view.

## Customization

  * **Content:** Modify the `<h3>`, `<div class="price">`, `<ul>`, and `<a>` tags within `index.html` to change the card titles, prices, features, and button links.
  * **Styling:** Adjust the CSS properties in `style.css` to customize colors, fonts, card dimensions, and glassmorphism effects.
  * **Tilt Effect:** In `main.js`, you can modify the `max`, `speed`, and `max-glare` options within `VanillaTilt.init()` to fine-tune the tilt animation.

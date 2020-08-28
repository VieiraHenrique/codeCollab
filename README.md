# HTML boilerplate and CSS reset

This repo contains a starting HTML/CSS project.

HTML is already linked to style.css and to script.js

The CSS contains already a "reset".

```css

*,
*::before,
*::after {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

html {
    font-size: 62.5%; /* Establish 1rem = 10px */
}

body {
    font-size: 1.6rem;
    font-family: sans-serif; /* INSERT FONT */
}

ul {
    list-style: none;
}

a {
    text-decoration: none;
}

img {
    width: 100%;
    height: auto;
}

```
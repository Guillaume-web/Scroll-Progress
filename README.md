# Scroll Progress Project

## Overview
This project is a demonstration of a unique web page where images move horizontally as the user scrolls vertically. It's a visually engaging way to navigate through content.

## Features
- Horizontal image movement on vertical scrolling
- Responsive design ensuring compatibility across various devices
- Utilization of modern HTML5 and CSS3 features

## Technologies Used
- HTML5
- CSS3

## How It Works
The main feature of this project is the animation tied to the user's scroll position. Images in the `.wrapper` class move horizontally across the viewport as the user scrolls down the page.

## Code Snippets

### HTML Structure
The HTML structure is straightforward, consisting of a series of `<section>` elements, each containing a `<div>` with class `container`. Inside the `wrapper` div, there are multiple `<figure>` elements each holding an `<img>` tag.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Meta Tags, Title, and CSS link -->
</head>
<body>
    <div class="wrapper">
        <!-- Images -->
    </div>

    <section>
        <!-- Section Content -->
    </section>

    <!-- Additional Sections -->
</body>
</html>
```

### CSS Structure

```Css
/* CSS Reset and Basic Styling */
/* ... */

.wrapper {
  /* Styling for image wrapper */
}

@keyframes slide {
  /* Keyframes for horizontal sliding effect */
}

/* Additional CSS */
```

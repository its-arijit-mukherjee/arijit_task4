# arijit_task4

A simple HTML/CSS webpage featuring a tranquil alpine landscape with a full-width **Click Me** button.

## Features

* Alpine landscape image displayed prominently on the page.
* Responsive viewport configuration.
* Centered scene container using viewport-based sizing.
* Full-width button positioned beneath the image.
* Gradient button background transitioning from yellow to green.
* Minimal styling with no external CSS framework or JavaScript.

## How It Works

### `index.html`

The HTML page defines a `.scenary` container containing:

* An alpine landscape image.
* A **Click Me** button.

The page loads the styles from `style.css`.

### `style.css`

The stylesheet:

* Removes the default body margin and padding.
* Positions the main content using viewport-relative margins.
* Sets the scene container to `50vw` wide and `80vh` high.
* Makes the landscape image span the full container width.
* Makes the button span the full width and gives it a gradient background.

## Getting Started

1. Keep `index.html` and `style.css` in the same directory.
2. Open `index.html` in a web browser.
3. The alpine landscape scene will be displayed with the styled button underneath.

## Technologies

* **HTML5**
* **CSS3**

# Product Preview Card

I built this responsive product preview card as a Frontend Mentor challenge. The page displays a Chanel fragrance, including its image, description, price, and add-to-cart button.

## Built with

- HTML5
- CSS3
- CSS Flexbox
- CSS media queries
- The HTML `<picture>` element for responsive images
- Google Fonts: Montserrat and Fraunces
- Local JPG, SVG, and PNG image assets

## Features

- Responsive mobile and desktop card layouts
- Mobile and desktop product images selected at the appropriate screen width
- Custom typography and colours based on the supplied style guide
- Button hover and keyboard-focus states

## Challenges I faced

One challenge was making sure the card looked good at bigger widths. I used Flexbox and responsive CSS to change the layout from a vertical card on smaller screens to a side-by-side card on larger screens.

Another challenge was using media queries in the HTML file. I used the `<picture>` element with a `<source>` media query so that the desktop product image is shown on screens that are at least 700px wide, while the mobile image is used on smaller screens.

## Running the project

No installation is needed. Open `index.html` in a web browser to view the project.

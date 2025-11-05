# About Me Web Page Example using the Bootstrap Navbar

=====================================

A simple web page showcasing an About Me web page using the Bootstrap collapsible fixed Navbar. The Bootstrap JavaScript is replaced with vanilla JavaScript, which handles additional functionality such as setting the active navigation link. It also improves the toggling behavior of the navbar by adding additional click handlers.

The Bootstrap grid system is replicated using custom media queries. The content is divided into 2 columns on medium and larger screens and 1 column on smaller screens. Gutters are used to add spacing between columns.

The width of the nav and main containers are responsive by using percent **%** units. The **max-width** is set to a fixed pixel value according to your design. Here, the max-width is set to **1024px** (a large tablet). For web pages with much greater content, you need to add more columns and a greater max-width.

The font size is responsive by using the CSS clamp function.

## Table of Contents

---

- [About Me Web Page Example using the Bootstrap Navbar](#about-me-web-page-example-using-the-bootstrap-navbar)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Customization](#customization)
  - [Technologies Used](#technologies-used)
  - [Installation](#installation)
  - [License](#license)
  - [Author](#author)
  - [Deployment](#deployment)

---

This project is a simple web page that showcases an About Me web page.

## Features

---

- Responsive design using Bootstrap collapsible fixed Navbar
- Simple and clean layout
  - 2 columns on medium and larger screens
  - 1 column on smaller screens
- Responsive font sizes
- Extensive use of CSS Custom Properties to allow for easy customization
- Custom media queries to replicate the Bootstrap grid system
- SEO metadata added for compatibility with iMessage and Slack
- JavaScript event handlers for collapsible navbar
- Includes contact information with email and LinkedIn links

## Customization

---

You can customize the web page by modifying the CSS variables in the `styles.css` file.

For example, you can change the (font) color and background color of each
container type:

- body
- navbar
- container
- header
- main
- card
- footer

You can also change the spacing between columns using the following variables:

- default gutter width
- gutter width for medium and larger screens

There are also variables for the border and box shadow properties of the cards.

The font size is responsive by using the CSS clamp function. The clamp function allows you to set a minimum and maximum font size and scaling parameters.

The [font-size calculator web site](https://www.marcbacon.com/tools/clamp-calculator/) is used to calculate the clamp function scaling parameters from these design values:

- font-size at the smallest design container width
- font-size at the largest design container width

To customize, visit this web site and enter new design values, then copy/paste the resulting clamp function.

A CSS container query is added to used to set the units of the container width and height: **cqw** and **cqh**. The output of the font-size calculator gives units of **vw** (view width), which need to be changed to **cqw** (container query width) in the clamp function generated.

## Technologies Used

---

- HTML5
- CSS3
- Bootstrap 5
- GitHub Pages for hosting

## Installation

---

1. Clone the repository using `git clone https://github.com/stefanzero/about-me-example.git`
2. Open the `index.html` file in a web browser to view the page

## License

---

This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for details.

## Author

---

- Stefan Musarra
- Email: [stefan0@stefan0.com](mailto:stefan0@stefan0.com)
- LinkedIn: [linkedin.com/in/stefan-musarra](https://www.linkedin.com/in/stefan-musarra-3bbaa952/)

## Deployment

---

Deployed on GitHub Pages: [About Me Example](https://stefanzero.github.io/about-me-example/)

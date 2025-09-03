# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview
The goal of this challenge was to build a clean and accessible blog preview card that presents content in a visually appealing and user-friendly way. 
This project was a great opportunity to practice semantic HTML, flexbox layout techniques, and responsive design for a small, reusable component.
By completing it, I improved my ability to translate a given design into code while keeping the structure maintainable and easy to read.

### Screenshot

![screenshot for desktop](./Screenshot%202025-09-03%20at%2003-53-18%20Frontend%20Mentor%20Blog%20preview%20card.png)
![screenshot for mobile](./Screenshot%202025-09-03%20at%2003-56-02%20Frontend%20Mentor%20Blog%20preview%20card.png)
![screenshot for active state](./Screenshot%202025-09-03%20at%2003-57-14%20Frontend%20Mentor%20Blog%20preview%20card.png)

### Links
- Live Site URL: [View live site here](https://JhayCodesDev.github.io/Blog-Preview-Card-Main/)
## My process
1. Setup

Downloaded the starter files and extracted them into a new project folder named blog-card-preview-main.
Reviewed the provided documents and design mockups to understand the project requirements and visual layout.

2. Structure

Built the HTML structure using semantic and meaningful class names:

#container – main wrapper for the card

.card-header – section for the image and title

.card-main – section for the blog description

.attribution – section for credit and links

This structure allowed me to organize the content clearly and follow best practices for accessibility and maintainability.

3. Styling

Used Flexbox to style the body and .card-header, ensuring content is aligned and spaced properly.

Added base styles for typography, colors, and card layout to match the design.

Implemented hover states to make the card interactive and visually engaging.

Styled the attribution section to be clean and readable at the bottom of the card.

4. Responsiveness

Applied a desktop-first approach, then used media queries for smaller screens.

Example for small devices:

@media screen and (max-width: 400px){
  #container {
    width: 80%;
  }
}


Adjusted widths, font sizes, and spacing to ensure the card looks good on mobile devices while maintaining alignment and readability.

5. Finishing Up

Cleaned up the CSS by grouping selectors logically.

Tested the card on multiple screen sizes to ensure responsiveness and hover effects worked correctly.

Prepared the project for deployment and documented the process in the README.

### Built with
- Semantic HTML5 markup: structured the card with meaningful tags and class names (#container, .card-header, .card-main, .attribution) for accessibility and maintainability

- Flexbox layout: used to align and space the body, card header, and main content effectively

- Container-based structure: organized the layout with a main wrapper and sub-wrappers for clear separation of content

- Desktop-first workflow: styled larger screens first, then applied media queries for smaller devices (from 400px downward)

- Responsive design techniques: ensured the card adapts gracefully across screen sizes

- Hover states: updated the design to include interactive hover effects for better user experience

### What I learned
This project reinforced my understanding of semantic HTML and Flexbox. It was a good way to practice applying what I learned from my previous project.

## Author

- Website - [@JhayCodesDev](https://github.com/JhayCodesDev)
- Frontend Mentor - [@yJhayCodesDev](https://www.frontendmentor.io/profile/JhayCodesDev)
- Twitter - [@JhayCodes](https://www.twitter.com/JhayCodes)

## Acknowledgments
Thanks to Frontend Mentor for providing such practical and challenging projects.

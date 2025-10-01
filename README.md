# Dynamic CSS Project: Focus on Motion, Variables, & Fluidity

This project is a clean, single-file CSS demonstration built to showcase advanced styling concepts, with a primary focus on dynamic motion, maintainability through variables, and fluid, function-based design.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size.

- Motion (Transitions & Animations): All interactive elements feature smooth, intentional motion using CSS **`transition`** properties and **`@keyframes`** to enhance user feedback and visual appeal.



### Links

- [Solution]()
- [Live Site](https://colourlibpreview.netlify.app/)

---

## My Process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow


### What I learned

- Precision Transition Tuning: I focused on choosing appropriate timing functions (like cubic-bezier) for different elements—a linear ease for subtle color changes, and a more aggressive curve for positional changes like button lifts.

- Decoupling Variables: Confirmed the benefit of separating color variables (e.g., --color-primary) from use variables (e.g., --button-hover-bg) for future design system flexibility.

- Animation Stacking: Ensured custom entry animations (scaleIn) do not conflict with or override the standard CSS transitions applied to hover states.

### Continued development

- Reduced Motion: Implement the @media (prefers-reduced-motion: reduce) query to gracefully disable all non-essential keyframe animations and soften transitions for users who prefer static layouts.


### Useful resources

- [MDN - CSS Variables](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_cascading_variables/Using_CSS_custom_properties) - This helped me for understanding variables well.

- [MDN - CSS Transition](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_transitions/Using_CSS_transitions) - This is an amazing article which helped me finally understand transitions.

## Author

- Frontend Mentor - [@poseidon0211-hub](https://www.frontendmentor.io/poseidon0211-hub)

## Acknowledgments


- I am deeply grateful to Mr. Albert for his dedicated support and encouragement throughout my learning journey in HTML and CSS. His clear explanations and practical advice were especially helpful in completing this project. His mentorship made a significant impact on my understanding and confidence in front-end development.


# Frontend Mentor - Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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


## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Github](https://github.com/yMeeraki/blog-preview-card)
- Live Site URL: [Netlify](https://blogpreviewfem.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS Flexbox
- CSS custom properties
- Mobile-first workflow


### What I learned

Throughout this project, I learned several valuable lessons that helped me improve my understanding of HTML, CSS, and responsive design principles.

1. **Semantic HTML**: Using clear and meaningful HTML tags improves both the structure and accessibility of a webpage. For example, I structured the content into proper sections like `<main>`, `<section>`, and `<footer>` to ensure readability.

```html
<main class="card">
  <section>
    <div class="heading">
      <img src="./assets/images/illustration-article.svg" alt="illustration-article">
      <h4>Learning</h4>
      <p>Published 21 Dec 2023</p>
    </div>
  </section>
</main>
```

2. **CSS Hover and Focus States**: I learned how to apply hover and focus states to interactive elements like buttons and cards to provide visual feedback to users, enhancing the user experience.

```css
.card:hover, .card:focus {
  box-shadow: 15px 15px 20px rgba(0, 0, 0, 0.2);
  transform: scale(1.02);
}
```
3. **Flexbox for Layout**: I deepened my understanding of using Flexbox for layout control. I applied Flexbox to align content properly within the card and ensure consistent spacing across different sections.

```css
div {
  display: flex;
  flex-direction: column;
  align-items: flex-start;
  gap: 1rem;
}
```

4. **Mobile-First Design**: I focused on building the layout with a mobile-first approach, which ensured the design looks great on smaller screens before scaling up for larger viewports.

```css
body {
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  min-height: 100vh;
  gap: 2rem;
}
```

### Continued development

In future projects, I plan to continue focusing on the following areas:

1. **Responsive Design**: I aim to improve my understanding of how to make websites look good on a variety of devices and screen sizes. I want to refine my use of media queries and grid/flexbox layouts for better adaptability.

2. **Accessibility**: Ensuring that websites are accessible to users with different needs is crucial. I plan to focus more on using ARIA labels, improving keyboard navigation, and testing screen reader compatibility.

3. **Advanced CSS Techniques**: I want to explore advanced CSS techniques like animations, transitions, and CSS variables to make my projects more dynamic and engaging.

4. **JavaScript Interactivity**: As I grow more comfortable with HTML and CSS, I aim to incorporate more JavaScript to enhance interactivity, such as creating modals, sliders, and form validation.


### Useful resources

- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - This guide was instrumental in understanding how to use Flexbox effectively for layout design. It provided clear examples and explanations that helped me implement Flexbox in this project.

- [MDN Web Docs - CSS Grid Layout](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout) - The MDN documentation on CSS Grid Layout was a valuable resource for understanding grid-based layouts. It offered comprehensive details and use cases that were helpful for structuring the content.

- [A11Y Project - Accessibility Checklist](https://a11yproject.com/checklist/) - This checklist was useful for ensuring that my project is accessible. It covers essential accessibility considerations and helped me identify areas for improvement.

- [Google Fonts - Figtree](https://fonts.google.com/specimen/Figtree) - The Google Fonts page for Figtree provided information on how to properly include the font in my project and how to use various font weights effectively.


## Author

- Website - [Yukti Gupta](https://www.linkedin.com/in/yukti-gupta-589974195/)
- Frontend Mentor - [@yMeeraki](https://www.frontendmentor.io/profile/yMeeraki)




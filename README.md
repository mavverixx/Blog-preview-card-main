# Blog preview card solution

This is a solution to the [Blog preview card challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/blog-preview-card-ckPaj01IcS). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
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

- View a clean and modern blog preview card that includes an image, title, description, and author information.
- Interact with the card with hover and focus states.
- Enjoy a responsive layout that adapts well on both mobile and desktop devices.

### Screenshot

![](/assets/images/Screenshot%202025-02-02%20at%2009.14.09.png)

### Links

- **Solution URL:** [https://github.com/yourusername/blog-preview-card](https://github.com/yourusername/blog-preview-card)
- **Live Site URL:** [https://yourusername.github.io/blog-preview-card/](https://yourusername.github.io/blog-preview-card/)

## My process

### Built with

- **HTML5** – Semantic markup for structuring the card.
- **CSS3** – Custom properties, Flexbox, and CSS Grid for a responsive design.
- **Mobile-first workflow** – Ensuring the design is optimized for smaller devices first.
- **[Optional: JavaScript]** – For any interactive enhancements if needed.

### What I learned

This project deepened my understanding of building flexible and responsive layouts using both Flexbox and CSS Grid. I also improved my skills in leveraging CSS custom properties for maintainable theming. For example, here's a snippet of the HTML structure used for the card:

```html
<div class="blog-card">
  <img src="images/blog-image.jpg" alt="Blog preview" class="blog-image" />
  <div class="blog-content">
    <h2 class="blog-title">
      Shift the overall look and feel by adding these wonderful touches to furniture in your home
    </h2>
    <p class="blog-description">
      Ever been in a room and felt like something was missing? Perhaps it felt slightly bare and uninviting. I’ve got some simple tips to help you make any room feel complete.
    </p>
    <div class="blog-footer">
      <img src="images/author-avatar.jpg" alt="Author avatar" class="author-avatar" />
      <span class="author-name">Micah Joe</span>
    </div>
  </div>
</div>
And here’s some of the CSS that structured the layout:

.blog-card {
  display: grid;
  grid-template-columns: 1fr;
  gap: 1rem;
  background-color: var(--card-bg, #fff);
  border-radius: 8px;
  overflow: hidden;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
}

.blog-image {
  width: 100%;
  height: auto;
}

.blog-content {
  padding: 1rem;
}

@media (min-width: 768px) {
  .blog-card {
    grid-template-columns: 40% 60%;
  }
}
Continued development
In future projects, I aim to:

Enhance interactivity with subtle JavaScript animations and transitions.
Further refine the responsive layout to handle more complex screen sizes.
Explore additional CSS techniques for improved accessibility and design refinements.
Useful resources
MDN Web Docs – A comprehensive resource for HTML, CSS, and JavaScript.
CSS-Tricks – Great for practical tips on responsive design.
Frontend Mentor – For additional projects and community inspiration.
Author

https://github.com/mavverixx

Acknowledgments
A big thanks to the Frontend Mentor community for the inspiring challenges and valuable feedback that helped me improve this project.



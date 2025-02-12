# Profile Card Component

This is a solution to the [Profile Card Component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/profile-card-component-cfArpWshJ). Frontend Mentor challenges help developers improve their coding skills by building real-world projects using best practices.

## Table of Contents

- [Overview](#overview)
  - [The Challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My Process](#my-process)
  - [Built With](#built-with)
  - [What I Learned](#what-i-learned)
  - [Useful Resources](#useful-resources)
- [Author](#author)

## Overview

### The Challenge

The goal of this challenge was to build a profile card component based on the provided design specifications. The key objectives included:

- Implementing a visually accurate layout using HTML and CSS
- Ensuring responsiveness for different screen sizes
- Applying background patterns correctly

### Screenshot

### Links

- 📂 **Solution URL:** [GitHub Repository](https://github.com/MATBMS/profile-card-component)
- 🌐 **Live Site URL:** [GitHub Pages](https://matbms.github.io/profile-card-component/)

## My Process

### Built With

- **Semantic HTML5** for clear and accessible markup
- **CSS Custom Properties** for reusable and maintainable styles
- **Flexbox** for efficient layout structuring

### What I Learned

One key takeaway from this project was how to incorporate multiple background images in CSS while maintaining proper positioning and responsiveness. Below is an example of how I used `background-image`, `background-position`, and `background-size` to achieve the design:

```css
main {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  background-image: url(./assets/images/bg-pattern-top.svg),
    url(./assets/images/bg-pattern-bottom.svg);
  background-position: -300px -500px, 160% -220%;
  background-repeat: no-repeat, no-repeat;
  background-size: 70%, 70%;
  background-color: #19a1ae;
}
```

This approach helped me control the positioning of the background elements dynamically.

### Useful Resources

- [MDN Web Docs - Background Image](https://developer.mozilla.org/en-US/docs/Web/CSS/background-image) - Helped clarify how multiple background images work.
- [CSS Tricks - Flexbox Guide](https://css-tricks.com/snippets/css/a-guide-to-flexbox/) - Provided great reference material for structuring the layout.

## Author

- Frontend Mentor - [@MATBMS](https://www.frontendmentor.io/profile/MATBMS)
- GitHub - [MATBMS](https://github.com/MATBMS)

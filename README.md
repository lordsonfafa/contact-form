# Frontend Mentor - Contact form solution

This is a solution to the [Contact form challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/contact-form--G-hYlqKJj). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

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

- Complete the form and see a success toast message upon successful submission
- Receive form validation messages if:
  - A required field has been missed
  - The email address is not formatted correctly
- Complete the form only using their keyboard
- Have inputs, error messages, and the success message announced on their screen reader
- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Links

- Solution URL: [Add solution URL here](https://www.frontendmentor.io/solutions/responsive-contact-form-using-bootstrap-diIEKXU3KX).com)
- Live Site URL: (https://contact-form-form.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Javascript
- [Bootstrap](https://getbootstrap.com)

### What I learned

During the course of this project, I learned how to display toast messages and how to validate forms

```js
if (form.checkValidity()) {
  toast.show();
  form.reset();
  form.classList.remove("was-validated");
} else {
  form.classList.add("was-validated");
}
```

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

I plan on further study in javascript as there is a lot of room for improvement in javasccript. It also was not bad for a start in bootstrap but I can do better if I put more work into it. I plan on focusing on these aspects for now.

### Useful resources

- [W3 schools](https://www.w3schools.com) -I would recommend w3schools to anyone new to bootstrap. This helped me whenever I forgot the correct bootstrap classes.

## Author

- Website - [Lordson Fafa Borngreat](https://www.your-site.com)
- Frontend Mentor - [@lordsonfafa](https://www.frontendmentor.io/profile/lordsonfafa)
- Instagram - [@lf_borngreat](https://www.instagram.com/lf_borngreat)

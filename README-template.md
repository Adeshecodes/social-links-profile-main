# Frontend Mentor - Social links profile solution

This is a solution to the [Social links profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/social-links-profile-UG32l9m6dQ). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Debugging](#debugging)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page
- View a responsive layout on mobile and desktop
- Experience a clean, centered profile interface with social links

### Screenshot

#### Mobile View(active state)

<img width="752" height="1800" alt="Screen Shot 2026-05-31 at 02 25 58" src="https://github.com/user-attachments/assets/41d01a18-0681-4336-adc5-678b708188ec" />

#### Desktop View(active state)

<img width="1920" height="837" alt="Screenshot 2026-05-31 at 02-44-17 Frontend Mentor Social links profile" src="https://github.com/user-attachments/assets/3ad2033f-b643-41bf-a0cf-99ef5e94e83f" />

### Links

- Solution URL: (https://github.com/Adeshecodes/social-links-profile-main)
- Live Site URL: (https://papaya-lamington-06e327.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- Flexbox
- Local fonts using "@font-face"
- Mobile-first workflow
- Responsive design with media queries

### What I learned

This project helped me strengthen my understanding of:
- Centering content using Flexbox
- Loading and using local fonts with @font-face
- Matching spacing, sizing, and typography to a design
- Structuring clean, semantic HTML
- Creating responsive layouts using media queries

Example of my @font-face setup:

```css
@font-face {
  font-family: 'Inter';
  src: url('./assets/fonts/Inter-Regular.ttf') format('truetype');
  font-weight: 400;
}
```

Example of my reponsive media query:

```css
@media (min-width: 768px) {
  .content {
    max-width: 400px;
    padding: 48px;
  }
}
```

### Debugging

During this project, I debugged several issues including:
- Fixing incorrect vertical centering using Flexbox
- Correcting local font loading errors with @font-face
- Adjusting layout spacing to match the design more accurately
- Removing duplicated CSS blocks that increased file size
- Resolving Git warnings (CRLF vs LF) and configuring a remote repository
- Improving responsive behavior on larger screens
- Fixing button sizing, padding, and hover states to match the design

These debugging steps helped me refine the UI and ensure the project behaves correctly across different devices.

### Continued development

This project showed me areas I want to grow in, especially:

- Getting better at matching the design exactly
- Making layouts that adapt smoothly to different screens
- Writing CSS that’s easier to maintain
- Challenging myself with more advanced Frontend Mentor tasks

### AI Collaboration

I used Microsoft Copilot mainly as a learning assistant. It helped me figure out things like local fonts, spacing, and responsiveness. It guided me through debugging and gave me clearer explanations when I got stuck. It was a helpful tool, but the actual building and decisions were mine.

## Author

- Website - [S.A.ADEYEMI](https://github.com/Adeshecodes)
- Frontend Mentor - [@Adeshecodes](https://www.frontendmentor.io/profile/Adeshecodes)


## Acknowledgments

Thanks to Frontend Mentor for providing this challenge and helping developers grow through real‑world projects.

A special thank you to <b>Akanimo Udoh</b>, who gave me helpful feedback on my previous Blog Card project. His advice about properly importing fonts and improving mobile spacing has been really useful, and I applied those lessons here. He also encouraged me to explore tools like clamp() for future projects, which I plan to look into.

# Social links profile

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### The challenge

Users should be able to:

- See hover and focus states for all interactive elements on the page

### Screenshot

![](./screenshot.jpg)

Add a screenshot of your solution. The easiest way to do this is to use Firefox to view your project, right-click the page and select "Take a Screenshot". You can choose either a full-height screenshot or a cropped one based on how long the page is. If it's very long, it might be best to crop it.

Alternatively, you can use a tool like [FireShot](https://getfireshot.com/) to take the screenshot. FireShot has a free option, so you don't need to purchase it. 

Then crop/optimize/edit your image however you like, add it to your project, and update the file path in the image above.

**Note: Delete this note and the paragraphs above when you add your screenshot. If you prefer not to add a screenshot, feel free to remove this entire section.**

### Links

- [github-code](https://github.com/ilypr/Social-links-profilem)
- [Live server](https://profile-with-social-links.netlify.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [React](https://reactjs.org/) - JS library
- [Next.js](https://nextjs.org/) - React framework
- [Styled Components](https://styled-components.com/) - For styles

**Note: These are just examples. Delete this note and replace the list above with your own choices**

### What I learned

Trougought this project I've learned how to use :root property to optimize the process of changing colors of a certain ellements as well as the use of @media tag to change the theme of webpage based on the user's device main theme colorway.

```html
<h1>:root usage for the colors</h1>
```
```css
/* ======== colors for the webpage ======== */
:root {
  --green: hsl(75, 94%, 57%);
  --white: hsl(0, 0%, 100%);
  --black: hsl(0, 0%, 0%);
  --grey-700: hsl(0, 0%, 20%);
  --grey-800: hsl(0, 0%, 12%);
  --grey-900: hsl(0, 0%, 8%);
}

/* ======= Webpage theme switch based on the device theme ======= */
@media (prefers-color-scheme: light) {
:root {
  --green: hsl(244, 75%, 63%);
  --white: hsl(0, 0%, 0%);
  --black: hsl(0, 0%, 100%);
  --grey-700: hsl(0, 0%, 95%);
  --grey-800: hsl(0, 0%, 88%);
  --grey-900: hsl(0, 0%, 96%);
}
}
```

Also, in this project I've depeened my knoweledge on :focus-fisible property, as well as to use :root colors to chanve the looks of links and button's hover effect using the var value.

```css
a:hover {
    background-color: var(--green);
    color: var(--black);         
}

/* ========== Footer ========== */
.license {
    font-size: 12px;
    text-align: center;
    color: var(--white);
}

.license a {
    text-decoration: none;
    color: var(--green);
    transition: 0.4s;
    border-radius: 2px;
    padding: 2px;
}

a:link {
    color: var(--white);
    text-decoration: none;
    font-weight: 800;
}

a:hover {
    background-color: var(--green);
    color: var(--black)
}
```

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

### AI Collaboration

Describe how you used AI tools (if any) during this project. This helps demonstrate your ability to work effectively with AI assistants.

- What tools did you use (e.g., ChatGPT, Claude, GitHub Copilot)?
- How did you use them (e.g., debugging, generating boilerplate, brainstorming solutions)?
- What worked well? What didn't?

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

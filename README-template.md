# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [About myself](#about-myself)
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

## About myself

Hi! I'm Jordan, an aspiring frontend developer. This means that this project is probably not the best learning material. That being said, i'll try to explain my process to the best of my abilities (which is kinda limited considering the fact that english isn't my first language, by the way my apologies for any mispellings or grammatical errors) in case someone happen to read this file. Worst case scenario, i can always come back to this project later and have fun at how bad i was back then!

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Project on GitHub](https://github.com/joanFaseDev/four-card-feature-app)
- Live Site URL: [Project hosted through Vercel](https://four-card-feature-app.vercel.app/)

## My process

### Analysis

- This project is made out of a few elements:

  - A _main_ element to act as a global container.
  - A head title, a _h1_ element will do. Inside the _h1_, we'll need a span for some strings have a bigger font-weight.
  - A paragraph _p_, probably using the default font size.
  - Four cards

- Each card have a different content but their layout is the same:

  - We can use a _section_ element as a card container.
  - Each card have a title which is good because _section_ element need to have one. Here, a _h2_ would do.
  - Then a paragraph _p_ and a svg image/icon located in the bottom right corner. We can use an _img_ element here.
  - Between the _section_ and its content, we'll add a _div_ element with a width in percentage. That way, we won't have to _padding_ for the cards.
  - Each card have a border top of a different color. Border style seems to be _inset_.
  - Also, each card use a light _box shadow_ and _border-radius_.

- Because the card's layout is the same, we can reuse a lot of code by using appropriate classes.

- The global layout for the mobile design is simple enough, one column for five rows. As for the desktop design, it's probably three columns for five rows. We'll use CSS Grid for the global layout and maybe Flexbox for the layout's cards.

- As usual, we'll start with the mobile design for it is easier to add complexity to a design than to remove from it.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
```

```css
.proud-of-this-css {
  color: papayawhip;
}
```

```js
const proudOfThisFunc = () => {
  console.log("🎉");
};
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

**Note: Delete this note and the content within this section and replace with your own learnings.**

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Example resource 1](https://www.example.com) - This helped me for XYZ reason. I really liked this pattern and will use it going forward.
- [Example resource 2](https://www.example.com) - This is an amazing article which helped me finally understand XYZ. I'd recommend it to anyone still learning this concept.

**Note: Delete this note and replace the list above with resources that helped you during the challenge. These could come in handy for anyone viewing your solution or for yourself when you look back on this project in the future.**

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

**Note: Delete this note and add/remove/edit lines above based on what links you'd like to share.**

## Acknowledgments

This is where you can give a hat tip to anyone who helped you out on this project. Perhaps you worked in a team or got some inspiration from someone else's solution. This is the perfect place to give them some credit.

**Note: Delete this note and edit this section's content as necessary. If you completed this challenge by yourself, feel free to delete this section entirely.**

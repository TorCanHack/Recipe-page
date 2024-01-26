# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

This challenge taught me how manipulate different aspects of a list. For example changing the colours of the markers. The markers of a list can be changed like this:

````css
li::markers {
  color: gold
}
````

I also learned how to space markers from the text in a list,by wrapping the text in a `<span>` tag then customizing `<span>` in css. Here's how I did it:
````html
<ul>
  <li><span>text</span></li>
</ul>
````

````css
span {
  position: relative;
  left: 1rem;

}
````

## Author

- Frontend Mentor - [@torcanhack](https://www.frontendmentor.io/profile/torcanhack)
- Twitter - [@pairofbrains](https://www.twitter.com/pairsofbrains)


## Acknowledgments

My hat tip goes to the awesome frontend mentor team. Thank you for this amazing challenge.

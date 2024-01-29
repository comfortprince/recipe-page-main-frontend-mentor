# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

## Overview

### Screenshot

![](./screenshot.jpg)

### Links

- Solution URL: [Solution URL](https://github.com/comfortprince/recipe-page-main-frontend-mentor)
- Live Site URL: [Live Site URL](https://github.io/comfortprince/recipe-page-main-frontend-mentor)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Mobile-first workflow

### What I learned

When styling a webpage using vanilla css, it is important to keep the css organized properly. I realized this when working on this challenge. As far as I can tell, most developers - including myself - prefer to have each css property and value pair on a new line. While this convention makes the code more readable, it doesn't take much for the file to reach hundreds of lines. This can make it difficult for the developer to find his way around the file when tweaking the layout.

After going through [stakeoverflow]() and [mdn web docs](), I realized there is no one size fits all solution to the problem. However there are few strategies that I found which can help with this problem:

- Pick a convention and be consistent
- Add comments (particularly block comments)
- Break a stylesheet into multiple smaller ones

The led me to organize the css as follows:
- index.css - main css file referenced in the index.html file
- base.css - contains general styles and custom properties for colors, typography etc
- colors.css - contains text and background color styles based on the custom properties
- utilities.css - in this case, it contains responsive containers
- page-specific.css - contains page specific styles. 

### Continued development

I will definitely redo this challenge using tailwind as it encourages developers to stay away from css. 

### Useful resources

- [Stakeoverflow](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwirprC1kP6DAxWPSUEAHcZ7AHsQFnoECCAQAQ&url=https%3A%2F%2Fstackoverflow.com%2Fquestions%2F146106%2Fhow-should-i-organize-the-contents-of-my-css-files&usg=AOvVaw3uUc6Wv54PC7WJWfA10nzU&opi=89978449) - This helped me realize the multiple ways to organize css. 
- [MDN Web Docs](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwirprC1kP6DAxWPSUEAHcZ7AHsQFnoECBcQAQ&url=https%3A%2F%2Fdeveloper.mozilla.org%2Fen-US%2Fdocs%2FLearn%2FCSS%2FBuilding_blocks%2FOrganizing&usg=AOvVaw1WIQwSGLpjsjaXdaAIycDT&opi=89978449) - This helped me realize the multiple ways to organize css.

## Author

- Frontend Mentor - [@Comfort](https://www.frontendmentor.io/profile/Comfort)

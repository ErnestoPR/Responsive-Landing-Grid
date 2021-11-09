# Frontend Mentor - Single price grid component solution

This is a solution to the [Single price grid component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/single-price-grid-component-5ce41129d0ff452fec5abbbc). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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

### The challenge

Users should be able to:

- View the optimal layout for the component depending on their device's screen size
- See a hover state on desktop for the Sign Up call-to-action

### Screenshot

Screenshots can be found in the MyDesign folder. It includes a screenshot for the desktop design and the mobile page.

### Links

- Solution URL: https://github.com/ErnestoPR/Responsive-Price-Grid
- Live Site URL: https://ernestopr.github.io/Responsive-Price-Grid/

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow

### What I learned

This was the first project I did from frontendmentor. I tried to make the design as close as possible to the photo design they provide. Still, for me the biggest challenge was figuring out the correct measurements of the original design. I managed to create a template with everything in place that looked pretty similar, but it looked scaled up and I couldn't figure out how to scale it down, as messing with the measurements meant rewriting the font size, borderline etc.

Another frustration that led to good knowledge was the borderline-radius. The way I wrote the code it requires to specify the radius individually for each grid element in order to get just one corner. I find this to be a bloated method and there had to be a simpler way. I tried changing the border-radius to the container in which the grid is, but the background color of the grid elements overlapped the border and I couldn't get it working.

I wanted to declare of colors using the var method in ::root, but using my color detection tools I noticed the the provided colors looked different, so I opted to manually color the individual aspects of the project. I don't like this approach as much as I'm trying to make the code as clean and easy to read as possible. 



### Continued development

I continued doing other projects from frontendmentor and in each one I learn something new. I tried the border-radius method on the container in another project and managed to get it working. By doing research I found out that I had to tweak the overflow property, since the default value is set to visible. Upon writing overflow: auto, the content inside the container clipped inside of it, making it not overlap when using border-radius. I've yet to apply this method in this project.

Another thing I had trouble and practiced in another project was centering the whole project. In this project I specified the margins in order to center the whole grid. The problem I had was, when converting the page to mobile, the margins would be too big and I had to rewrite the margins in order to fit the whole content. I found this to be tedious as I believe there must be a way to do this automatically and responsive by default, without having to mess around too much with @media. In other projects I tried converting all of the body into a flex and centering it using justify-content and align-items, and creating the grid inside the flex. I've yet to try that in this project.

For the next projects I would like to experiment more with the sizes of the elements and the fonts, by using em and rem instead of px, as I noticed the become responsive better than px. 

I've continued doing research on how to create buttons for these projects. I've read online that the community is divided as to what the best approach is to make a button that links to an external page. The method I used was putting a button inside an anchor, which works but a lot of people believe this is wrong html and is not accepted. I did not want to take a JS approach to a button, neither I wanted to CSS an anchored link to make it look like one. For the upcoming projects I want to try to make a functional button by using the form method along with input or button. I need to do more research on this as I need to figure out the correct way to use the (action) within (form) to make it work as a button instead of trying to submit something. 

The favicon is not used in this project since I didn't really know what it was. Upon doing other projects I learned about it and might implement it in here further down the road.

### Useful resources

- [Overflow](https://www.w3schools.com/csS/css_overflow.asp) - w3schools is a great resource to find the answer fast and on point.
- [freecodecamp.org forums](www.freecodecamp.org) - Amazing place to get started and full of useful articles to help you grow as a developer.



## Author

- Github - [ErnestoPR](https://github.com/ErnestoPR)
- Frontend Mentor - [@ErnestoPR](https://www.frontendmentor.io/profile/ErnestoPR)
- Codepen - [@CangrejoPR](https://codepen.io/CangrejoPR)





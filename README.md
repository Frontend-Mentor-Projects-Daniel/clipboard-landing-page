# Frontend Mentor - Clipboard landing page solution

This is a solution to the [Clipboard landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/clipboard-landing-page-5cc9bccd6c4c91111378ecb9). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page

### Screenshot

![screenshot](./develop/assets/images/clipboard-screenshot.png)

### Links

You can find the live version of the site [here](https://stalwart-bavarois-15c13b.netlify.app/).

## My process

I wanted to test out cube css, which was created by Andy Bell, and it is a CSS methodology geared towards simplicity, pragmatism, and consistency. CUBE stands for “Composition Utility Block Exception” and is a tool-agnostic methodology.

I used the tool [utopia.fyi](https://utopia.fyi/) in order to generate a fitting type-scale for the project then I added those font-size and space scales as css custom properties and assigned them to my elements

After my reset and global styles, I added my utility classes next, Andy Bells preferred way of doing this seems to be to use TailwindCSS for adding styles using utility classes. I did it manually and indeed, while I don't know whether adding the styles using tailwind or just adding them into their blocks would be more preferrable to me, doing this by hand, especially for hover states is time consuming

I added in my compositions next, the composition layer’s job is to create flexible, component-agnostic layout systems that support as many variants of content as possible. These sort of skeletal layers that can work in any circumstance without caring what goes in as children are surprisingly difficult, in this instance I used the compositions from Heydon Pickering's [EveryLayout](https://every-layout.dev/), but I will create my own in the future

After doing the hard work, all that was left were the individual blocks and in this project, a lot my code could be reused which actually saved me more time in the long run then if I just did this normally.

My conclusion is that I prefer the CUBE way of doing things and I like not having to write media queries for changing font-sizes and less (_or no_) media queries for my block layouts

## Built with

- Semantic HTML5 markup
- CSS
- CUBE css methodology
- Fluid Type and Space Scales
- Mobile-first workflow

## What I learned

- There are many ways to cut down on media queries!
- After spending a bit of time learning how to use Cube CSS, I ended up just really needing to add a few styles and rules and could do the rest of the components quickly - the footer was actually the hardest part since I did that one mostly manually

## Useful resources

- [utopia](https://utopia.fyi/) - For generating fluid type and space scales
- [EveryLayout](https://every-layout.dev/) - For creating base skeletal layouts that work regardless of what their descendants are
- [Cube css](https://cube.fyi/) - For explaining the concept of CUBE CSS

## Author

- [Portfolio Website](https://daniel-arzani-portfolio.netlify.app/)
- [Frontend Mentor Profile](https://www.frontendmentor.io/profile/DanielArzani)

## Acknowledgments

- The frontend mentor platform for the challenge and the design files

- The frontend mentor slack platform which is incredibly helpful for peer review, especially on the topics of accessibility and best practices

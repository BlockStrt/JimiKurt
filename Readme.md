###  Jimi vs Kurt

## Table of contents

- [Overview](#overview)
  - [Links](#links)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Email](#email)

## Overview
 Focused on new technologies within Javascript making animations
 really easy creating a carousel menu bar. Also used the same 
 technology to create a unique slideshow.


### Links

- Solution URL: (https://github.com/BlockStrt)


### Built with

- JavaScript
- CSS 
- HTML5
- GSAP

### What I learned
GSAP is a javascript technology, this is a new way for me to implement animations
while writing neat code at the same time.


``` Unique Slide Show Gsap Func Ex.

const currentImage = images[current]
    const flipTimeline = gsap.timeline()

    flipTimeline
    .set(currentImage, {x: 0})
    .to(currentImage, {
      x: direction,
      rotation: midAngle,
      scale: 1.5
    })
    .set(currentImage, {zIndex: z})
    .to(currentImage, {
      x: 0,
      rotation: () => {
        return 16 * Math.random() - 8
      },
      scale:1
    })
    
   
    current = current + 1
    current = current % images.length
  })
```

### Continued development
Using what I've learned I will do some more advanced things the next Repo commit.


## Author

- Website - (https://github.com/BlockStrt)
          - (https://twitter.com/BlckStrtr)
          - (https://blockstrt.github.io/jimiKurt/)
          

## Email
(Blockstarter34@Gmail.com)

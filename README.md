# Profile Card Component

 Make It Real - This is a solution to the Profile Card Component Project of the Make It Real course.


## Table of contents
 1. [The challenge](#the-challenge)
 2. [Screenshot](#screenshot)
 3. [My process](#my-process)
 4. [Built with](#built-with)
 5. [What I learned](#what-i-learned)
 6. [Useful resources](#useful-resources)
 7. [Author](#author)
 8. [Acknowledgments](#acknowledgments)


### The challenge
 Users should be able to:
 Be able to Watch the card component regardless of the screen size (mobile or desktop).

### Screenshot

#### Mobile design
![Mobile design](https://github.com/dcquinche/ProfileCard/blob/main/design/Mobile.png)

#### Desktop design
![Desktop design](https://github.com/dcquinche/ProfileCard/blob/main/design/Desktop.png)


### My process
First we organized the HTML structure for the mobile design and we added the layouts for both designs.


### Built with
- HTML
- CSS
- Mobile-first workflow
- Media Query


### What I learned

- How to add a icon to the browser tab.

```
<link rel="icon" type="image/x-icon" href="../scr/images/favicon.png">

```

- How to overlay one image on another with z-index property.

```

html, body{
    position: relative;
}

#topCircle {
    position: absolute;  
    z-index: -1;
}

#component {
    position:absolute;
    z-index: 1;
}

```

### Useful resources	
[Z-index property](https://es.stackoverflow.com/questions/174400/c%C3%B3mo-superponer-dos-im%C3%A1genes) - You can find examples to see how to use it.


### Author
Diana Carolina Quinche Velez -
[Linkedin](https://www.linkedin.com/in/diana-carolina-quinche-v%C3%A9lez-06b9791b3/)


### Acknowledgments
Special acknowledgments to my team partners Sebastian Muñoz - Juan Camilo Orjuela and our mentor Cristian Moreno.

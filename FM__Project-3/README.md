# Frontend Mentor - NFT preview card component solution
This is a solution to the [NFT preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/nft-preview-card-component-SbdUL_w0U). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Overview
## Links

- Solution URL: https://github.com/CristianArielDelgado/CristianArielDelgado.github.io/tree/main/FM__Project-3
- Live Site URL: https://cristianarieldelgado.github.io/FM__Project-3/index.html

### My process
### Built with
- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles


#### Author

- Website - [Cristian Ariel Delgado](https://cristianarieldelgado.github.io/index.html)
- Frontend Mentor - [@CristianArielDelgado](https://www.frontendmentor.io/profile/CristianArielDelgado)




### What I learned
'''
.main__container-image::before{
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background-color: var(--cyan);
  opacity: 0;
  transition: opacity 0.5s ease-in-out;
  border-radius: 1rem;
}
.main__container-image:hover::before{
  opacity: 0.4;
}
.main__container-image img:hover{
  position: relative;
  color: var(--cyan);
}
.main__container-image:hover::after{
  content: "";
  position: absolute;
  /* Centramos la imagen */
  top: 50%;
  left: 50%;
  /* Fin centrar la imagen */
  transform: translate(-50%, -50%);
  /* Tamaño imagen */
  width: 3.2rem;
  height: 3.2rem;
  /* Fin tamaño imagen */
  background-image: url("../assets/images/icon-view.svg");
  background-size: cover;
  z-index: 1;
}
'''
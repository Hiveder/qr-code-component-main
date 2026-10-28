# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
  - [AI Collaboration](#ai-collaboration)
- [Author](#author)

## Overview

### Links

- Solution URL: (https://hiveder.github.io/qr-code-component-main/)
- Live Site URL: [https://www.frontendmentor.io/profile/hiveder]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties


### What I learned

La construccion de este proyecto menor me ha llevado a profundizar en el estudio de los elementos HTML y varias propiedades de CSS, a fin de enterder mas a fondo sus utilidades y aplicacion correcta en cada lenguaje. A continuacion algunos ejemplos:

```html
<h1>Some HTML code I'm proud of</h1>
<section id="contenedor">
    <img class="width" src="images/image-qr-code.png"/>
    <h3 class="width"></h3>
    <p class="width"></p>
  </section> /*aprendi diferencia entre clase y id, y el como diferentes etiquetas pueden compartir una misma clase*/
```
```css
body {
  margin: 90px; /*tambien aprendi mucho sobre las propiedades Padding y border*/
  margin-bottom: 0px; 
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
}
```
```css
@media (max-width: 320px) {
  /* se agrego media querry para modificar los Estilos
   para celulares con pantallas de hasta 320px*/

  body {
    margin:0px;
    margin-top:20px;
  }

   #contenedor {
    width: 210px;
  }

  .width { 
    width: 190px;
  } 

p {
    margin-bottom:10 px;
}
.attribution {
    margin-top:30px;
}
}
```

### Continued development

A pesar de comprender el uso de diversas propiedades CSS, entiendo que mis cconocimientos aun son limitados y muchas de las cosa se pueden hacer de una manera mas simple, me esforzare por ampliar mis conocimientos sobre los lenguajes aplicados.

### Useful resources

- [HolaMundoDev]: (https://www.youtube.com/@HolaMundoDev) - Las manera de explicar de este profesor me facilito mucho el aprender y comprender mucho acerca de HTML y CSS, a mi parecer su metodologia se adapta a mi forma de aprender, es por ello que contuare aprendiendo de sus cuursos.
- [Taller de programacion para novatos](https://drive.google.com/file/d/1wM87Ff7CfcP-qiNWRfVQFzV7rVqm7ehO/view) - Introdujo a la aplicacion de los conceptos que ya sabia, desde un punto de vista mas practico.
- [Flexboxfroggy]: (https://flexboxfroggy.com/#es) - Me ayudo comprender, mediante la practica, las propiedade flex, asi como sus valores!


### AI Collaboration

- Utlice las herramientas Geminis, Github y claude.
- En general, las aplique para verificar valores y propiedades de CSS, siendo novata, no tenia muy claro que valores eran aplicables a las propiedades. Esto me ayudo a solventar muchos problemas de incongruencias.
- Se tuvo problemas con los choque entre valores de diferentes propiedades, pero una vez ajustados los valores de margin de los elementos, agregado el display: flex; al elemento body y ajustada la propiedad width de #contenedor, las colisiones fueron solucionadas.

**Note: Delete this note and the content above if you didn't use AI, or replace with your own experience.**

## Author

- Website - [Hiveder](https://github.com/Hiveder)
- Frontend Mentor - [@hiveder](https://www.frontendmentor.io/profile/hiveder)


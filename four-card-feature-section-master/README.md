# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

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
- [Acknowledgments](#acknowledgments)



## Overview

This project challenged me to create a website that had a title, subtitle and paragraph centered in the header of the screen, in addition to presenting four cards that had a title, paragraph and image.
Website must be responsive for desktop (1440p) and mobile (375p) screens
### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Screenshot

![](./Capturas/Captura%20Desafio%20Desktop.jpg)
capture taken from the desktop.


![](./Capturas/Captura%20Desafio%20Mobile.png)
Capture taken from the mobile screen.


### Links

- Solution URL:(https://github.com/Rodjfreitas/four-card-feature-section-master.git)
- Live Site URL:(http://127.0.0.1:5500/four-card-feature-section-master/index.html)

## My process

I started by styling the header. Editing Title, Subtitle and Paragraph.

Then it was time to create the div for the cards. Separating them into title, paragraph and image.

The most challenging moment was adjusting the styling of the cards on screen. The first challenge was to edit the positioning of the cards for a 1440px screen, as I was using the display flex property, and it displayed the cards in a row on the screen. However, the challenge suggested that I present the cards on the screen in the form of a cross, with a green card on the left, two cards (red and orange) centered and a blue card on the right. This was one of the most difficult moments during the project.

Then I came across another challenge proposed by the project: The requirement that the screen fit between 375px and 1440px. I came across the need to make changes to the code so that I could include the presentation in 375px. It was the moment that my research put me in front of the media query.

The biggest problem faced with media query setup is the need to adjust the blue card manually to align with the screen with the others. The margins are not linear with the other cards, and I needed to edit the left, top and left margin properties of this card. (I'm still looking for a way to optimize this situation).

Finally, the process needs some tweaking, and I'm finally making the changes to streamline the code.

This challenge was fantastic, as it took me out of my comfort zone to work with properties unknown to me until then.

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Cards



### What I learned

Positioning objects is a task that requires a lot of patience to learn, especially for beginners. I managed to improve my skills a lot in this task, but I believe that I still have a lot to learn in relation to this topic. Mainly because I feel that I am not happy with the code used to fit the cards on the mobile screen, as I had to edit the placement of a specific card separately so that it would line up with the other cards.


```css
      .Red{border-top: 4px solid #EA5353;position: relative;clear: both;top: 20px;margin-bottom: 12px;}
      .Green{border-top: 4px solid #45D3D3;position: relative;clear: both;top:0px;margin-bottom: 5px; }
      .Orange{border-top: 4px solid #FCAF4A;position: relative;clear: both;top:30px;}
      .Blue{border-top:  4px solid #549EF2;position: relative;clear: both;top:845px;left: -5px;}
```

I used the margin-bottom, top and left properties individually on the cards, as I wasn't successful in universally editing them on the div where the cards were inserted.

### Continued development

I will improve myself in object placement studies to work more efficiently in future projects.

### Useful resources

- (https://programandosolucoes.dev.br/2021/06/22/card-html-css/#:~:text=Como%20fazer%20card%20com%20HTML%20%2B%20CSS%201,V%C3%ADdeo%206%20C%C3%B3digo%20fonte%20...%207%20Refer%C3%AAncias%20) - This Site helped me to create the cards, since it was a new content for me, who had little knowledge.
- (https://www.youtube.com/watch?v=3l8fIh4y54E&t=314s) - This link helped me understand the application of the media query to apply responsiveness to the site.


## Author

<a href="https://www.linkedin.com/in/rodrigo-freitas-5b5a018a/" target="_blank"><img src="https://img.shields.io/badge/-Linkedin-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"> <a href="https://www.instagram.com/rodrigojdefreitas/" target="_blank"><img src="https://img.shields.io/badge/-Instagram-C13584?style=for-the-badge&logo=instagram&logoColor=white"></a> <a href="https://github.com/Rodjfreitas" target="_blank"><img src="https://img.shields.io/badge/-Github-333333?style=for-the-badge&logo=github&logoColor=white">

</a> <a href="mailto:rodjfreitas@gmail.com" target="_blank"><img src="https://img.shields.io/badge/Gmail-DB4437?style=for-the-badge&logo=gmail&logoColor=white"></a> <a href="mailto:rodrigofreitas2011@live.com" target="_blank"><img src="https://img.shields.io/badge/Outlook-00A4EF?style=for-the-badge&logo=MicrosoftOutlook&logoColor=white"></a>



## Acknowledgments

This project was only possible with the help of the mentorship Conquiste Sua Vaga, through the people of Pedro Marins, Henrique de Andrade and all the wonderful structure they have in the Code community. With them I'm learning to challenge myself and acquire habits I've never practiced before.

My wife Natália, who every day encourages me to program and continue dedicating all my time to this purpose.



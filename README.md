# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview

### Screenshot

![Screenshot 2024-02-11 at 00-25-28 Frontend Mentor QR code component](https://github.com/aclf12/qr-code_challenge/assets/43484517/8018f4ea-cded-41db-b4af-3674afcd1607)
![Captura de tela 2024-02-11 - 00 24 12](https://github.com/aclf12/qr-code_challenge/assets/43484517/ccbfdef3-d6b1-4cbb-b37f-43317378d2b9)

### Links

- Solution URL: [https://github.com/aclf12/qr-code_challenge.git]
- Live Site URL: [https://aclf12.github.io/qr-code_challenge/]

## My process

### Built with

- Semantic HTML5 markup
- Border - box
- CSS Grid
- Mobile-first workflow

### What I learned

As expected from a beginner, you may notice some difficulties in building this website. It's literally the first time I've made a website on my own. However, as a good student, I studied some ways to solve my little problem, thus helping my learning. The biggest difficulty I had was in relation to CSS, where I'm still seeing the issue of fixed sizes, etc.

The first point was the use of the “main” tag. When I researched it, I saw that it is well used due to the semantics of main. Unlike the div, it responds to the browser by showing the main part of the website.

```html
<main class="principal">
     <img src="images/image-qr-code.png"/>
     <h1>Improve your front-end skills by building projects</h1>
     <p>Scan the QR code to visit Frontend Mentor and take your coding skills to the next level</p>
</main>
```
The biggest difficulty I had with CSS was the issue of margins conflicting with "width" and "height". With some research, I discovered that when we use these two to determine content size, we use either "margin-inline" or "margin-right" / "margin-left", both in "auto".
```css
.principal{
    width: 300px;
    height: 470px;
    margin-right: auto;
    margin-left: auto;
    padding-top: 15px;
    margin-bottom: 10%;
    background-color: white;
    border-radius: 20px;
    box-shadow: 8px 8px 15px rgba(0, 0, 0, 0.4);
    
}
```

### Continued development

In this project I did not use anything about JavaScript. However, I intend to start using it in the future. This may be the most difficult part of learning, since we are talking about Programming Language.

### Useful resources

- [DevMedia]([https://www.example.com](https://www.devmedia.com.br/css-text-shadow-e-box-shadow/36826)) - Helped me with the "box-shadow" issue
- [Figma](https://www.figma.com/) - Helped with designing the layout

## Author

- GitHub - [Ana Carolina](https://github.com/aclf12)
- Frontend Mentor - [@aclf12](https://www.frontendmentor.io/profile/aclf12)
- Instagram - [@aclf12](https://www.instagram.com/aclf12/)

## Acknowledgments

I want to thank everyone who stopped to give advice on the subject, as well as those who were willing to help me.

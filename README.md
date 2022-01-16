# Frontend Mentor - Stats preview card component solution

This is a solution to the [Stats preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/stats-preview-card-component-8JqbgoU62). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)

## Overview

### The challenge

Users should be able to:

- View the optimal layout depending on their device's screen size

## My process

### Built with

- Semantic HTML markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- [Styled Components](https://styled-components.com/) - For styles

### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<h1>Some HTML code I'm proud of</h1>
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Stats Preview Card Component</title>
    <link rel="stylesheet" href="styles.css" />
    <link rel="icon" href="favicon-32x32.png" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@600&display=swap"
      rel="stylesheet"
    />
    <link
      href="https://fonts.googleapis.com/css2?family=Lexend+Deca:wght@100;200&display=swap"
      rel="stylesheet"
    />
  </head>

  <body>
    <div class="main-div">
      <div class="head-div"></div>
      <div class="mid-div">
        <div class="mid1"></div>
        <div class="mid2">
          <h1>Get <span>insights</span> that help your business grow.</h1>
          <p class="p1">
            Dicover the benefits of data analytics and make better decisions
            regarding revenue, customer experience, and overall efficiency.
          </p>
          <h2 class="p2">10k+</h2>
          <h2 class="p3">314</h2>
          <h2 class="p4">12M+</h2>
          <p class="p5">COMPANIES</p>
          <p class="p6">TEMPLATES</p>
          <p class="p7">QUERIES</p>
        </div>
        <div class="mid3">
          <img class="img" src="image-header-desktop.jpg" alt="image" />
        </div>
        <div class="mid4"></div>
      </div>
      <div class="foot-div"></div>
    </div>
  </body>
</html>
```

```css
.proud-of-this-css {
  body {
    background-color: white;
}

.main-div {
    width: 1400px;
    height: 600px;
    background-color: hsl(233, 47%, 7%);
}
.head-div {
    width: 1400px;
    height: 120px;
    background-color: hsl(233, 47%, 7%);
}
.mid-div {
    width: 1400px;
    height: 300px;
    background-color: hsl(233, 47%, 7%);
}
.foot-div{
    width: 1400px;
    height: 120px;
    background-color: hsl(233, 47%, 7%);
}
.mid1{
    width: 200px;
    height: 300px;
    background-color: hsl(233, 47%, 7%);
    float: left;
}

.mid2{
    width: 400px;
    height: 300px;
    background-color: hsl(244, 38%, 16%);
    float: left;
    padding-left: 50px;
    padding-right: 50px;
    padding-top: 30px;
    border-top-left-radius: 10px;
    border-bottom-left-radius: 10px;
    
}
.mid3 {
    width: 450px;
    height: 330px;
    background-color: hsl(277, 64%, 61%);
    float: left;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
}
.mid4{
    width: 250px;
    height: 300px;
    background-color: hsl(233, 47%, 7%);
    float: left;
}
.img{
    width: 450px;
    height: 330px;
    float: left;
    border-top-right-radius: 10px;
    border-bottom-right-radius: 10px;
    mix-blend-mode: multiply;
    opacity: 0.75;
  
}

h1 {
    color: hsl(0, 0%, 100%);
    font-weight: 700;
    font-family: 'Inter', sans-serif;
}

.p1 {
    color: hsla(0, 0%, 100%, 0.6);
    font-family: 'Lexend Deca', sans-serif;
}
.p2 {
    display: inline;
    color: hsl(0, 0%, 100%);
    font-family: 'Inter', sans-serif;
    
}

.p3 {
    display: inline;
    margin-left: 100px;
    color: hsl(0, 0%, 100%);
    font-family: 'Inter', sans-serif;
    
}
.p4 {
    display: inline;
    margin-left: 100px;
    color:hsl(0, 0%, 100%);
    font-family: 'Inter', sans-serif;
    
}
.p5 {
    display: inline;
    color: hsla(0, 0%, 100%, 0.6);
    font-size: 15px;
    font-family: 'Lexend Deca', sans-serif;
}
.p6 {
    display: inline;
    margin-left: 60px;
    color: hsla(0, 0%, 100%, 0.6);
    font-size: 15px;
    font-family: 'Lexend Deca', sans-serif;
}
.p7 {
    display: inline;
    margin-left: 75px;
    color: hsla(0, 0%, 100%, 0.6);
    font-size: 15px;
    font-family: 'Lexend Deca', sans-serif;
}
span {
    color: hsl(277, 64%, 61%);
}
```

### Continued development

I was not able to add any kind of accent color to the image which is specified so i would like to learn that concept in
the upcoming challenges.

### Useful resources

- (ttps://www.w3schools.com/html/html_css.asp) - This helped me for styling the website. I really liked this website and will use it going forward.

(https://developer.mozilla.org/en-US/docs/Web/HTML) - This is an amazing article which helped me finally understand HTML. I'd recommend it to anyone still learning this concept.

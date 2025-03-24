# 🧬 Website Animation Reveal GSAP

<div align="center">
  <img src="https://github.com/um-xair/html-css-js-website-animation/blob/main/main.png" />
  <img src="https://github.com/um-xair/html-css-js-website-animation/blob/main/main1.png" />
</div>  
  
## About 
This repository contains code for website animation creation using GSAP (GreenSock Animation Platform). GSAP is a powerful JavaScript library for creating high-performance animations.

## Live Demo  
Check it out here: [Website Animation Reveal](#) 

## HTML Structure
The HTML structure defines the layout of the webpage, including loader elements, navigation, footer, etc.

## CSS
The CSS file (`styles.css`) is linked to the HTML file to apply styling to various elements on the webpage.

## JavaScript (GSAP)
The JavaScript code includes animations using the GSAP library. Here's a breakdown of the animations:

### Loader Animation
The loader animation is created using GSAP. Initially, the loader clips (`clip-top` and `clip-bottom`) are animated to expand vertically (`height: "50vh"`) with a duration of 2 seconds and an easing effect of "power4.inOut". The marquee elements inside the loader are also animated to move to the centre of the screen (`top: "50%"`) with a duration of 3.5 seconds and an easing effect of "power4.inOut".

### Marquee Animation
The marquee elements inside the loader are animated to move from left to right. The marquee elements inside `clip-top` and `clip-bottom` are animated to move from right to left (`left: "100%"`), while the marquee element inside `clip-center` is animated to move from left to right (`left: "-50%"`). These animations have a duration of 5 seconds and an easing effect of "power3.inOut".

### ClipPath Animation
Finally, the clip path of the loader clips (`clip-top` and `clip-bottom`) is animated to reveal the content underneath. This animation starts after a delay of 6 seconds. The clip path of `clip-top` is animated to `inset(0 0 100% 0)` (revealing the bottom part of the loader), and the clip path of `clip-bottom` is animated to `inset(100% 0 0 0)` (revealing the top part of the loader). These animations have a duration of 2 seconds and an easing effect of "power4.inOut". Additionally, the opacity of the marquee elements is animated to 0 simultaneously (`opacity: 0`) with a duration of 1 second and an easing effect of "power2.inOut".

## 🛠️ Technologies Used  
<p align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" width="80" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" width="80" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" alt="JavaScript" width="80" />
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/tailwindcss/tailwindcss-plain.svg" alt="Tailwind CSS" width="80" />
  <img src="https://raw.githubusercontent.com/danilosetra/devicon/master/icons/gsap/gsap-original.svg" alt="GSAP" width="80" />
</p>


### 🧬 Website Animation using HTML CSS Javascript GSAP | by UM-XAIR
<div align="center">
<img src="https://github.com/um-xair/html-css-js-website-animation/blob/main/main.png" />
<br />
<img src="https://github.com/um-xair/html-css-js-website-animation/blob/main/main1.png" />
</div>  
  
<br />

This repository contains code for creating a website animation using GSAP (GreenSock Animation Platform). GSAP is a powerful JavaScript library for creating high-performance animations.

## HTML Structure
The HTML structure defines the layout of the webpage, including loader elements, navigation, footer, etc.

## CSS
The CSS file (`styles.css`) is linked to the HTML file to apply styling to various elements on the webpage.

## JavaScript (GSAP)
The JavaScript code includes animations using GSAP library. Here's a breakdown of the animations:

### Loader Animation
The loader animation is created using GSAP. Initially, the loader clips (`clip-top` and `clip-bottom`) are animated to expand vertically (`height: "50vh"`) with a duration of 2 seconds and an ease effect of "power4.inOut". The marquee elements inside the loader are also animated to move to the center of the screen (`top: "50%"`) with a duration of 3.5 seconds and an ease effect of "power4.inOut".

### Marquee Animation
The marquee elements inside the loader are animated to move from left to right. The marquee elements inside `clip-top` and `clip-bottom` are animated to move from right to left (`left: "100%"`), while the marquee element inside `clip-center` is animated to move from left to right (`left: "-50%"`). These animations have a duration of 5 seconds and an ease effect of "power3.inOut".

### ClipPath Animation
Finally, the clip path of the loader clips (`clip-top` and `clip-bottom`) is animated to reveal the content underneath. This animation starts after a delay of 6 seconds. The clip path of `clip-top` is animated to `inset(0 0 100% 0)` (revealing the bottom part of the loader), and the clip path of `clip-bottom` is animated to `inset(100% 0 0 0)` (revealing the top part of the loader). These animations have a duration of 2 seconds and an ease effect of "power4.inOut". Additionally, the opacity of the marquee elements is animated to 0 simultaneously (`opacity: 0`) with a duration of 1 second and an ease effect of "power2.inOut".


<br />
Inspiration from the [Codegrid YouTube channel](https://www.youtube.com/@codegrid) 🫶

<br />

## Collaborate With Me
If you're interested in collaborating or have any inquiries, feel free to reach out via email or WhatsApp!

<div align="center">
<a href="mailto:umairaxin@gmail.com" target="_blank">
  <img src="https://img.shields.io/badge/email-%23000000.svg?&style=for-the-badge&logo=gmail&logoColor=white&color=FF0000" alt="email" height="50" />
</a>
<a href="https://wa.me/01162260866" target="_blank">
  <img src="https://img.shields.io/badge/whatsapp-%23000000.svg?&style=for-the-badge&logo=whatsapp&logoColor=white&color=006400" alt="whatsapp" height="50" />
</a>
<a href="https://www.tiktok.com/@devxair" target="_blank">
  <img src="https://img.shields.io/badge/tiktok-%23000000.svg?&style=for-the-badge&logo=tiktok&logoColor=white&color=545454" alt="tiktok" height="50" />
</a>
  <a href="https://www.behance.net/devxair" target="_blank">
  <img src="https://img.shields.io/badge/behance-%231E90FF.svg?&style=for-the-badge&logo=behance&logoColor=white&color=003ECB" alt="behance" height="50"/>
</a>
</div>



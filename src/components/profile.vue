<template lang="pug">
section#profile
  .section__pic-container
    img.section__pic-container-img(src='../assets/image/profile.jpeg' alt='juan profile picture')
  .section__text
    p.section__text__p1 Hello, I&apos;m
    h1.title Juan Esteban
    p.section__text__p2 Full stack Developer
    .btn-container
      button.btn.btn-color-2
        a(href='/cvjuanestebanquiramalopez.pdf' target="_blank" download) Download CV
      button.btn.btn-color-1(onclick="location.href='./#contact'")
        | Contact Info
    #socials-container
      a(href="https://www.linkedin.com/in/jquirama-dev-bitan/" target="_blank")
        img.icon(src='../assets/image/linkedin.png' alt='My LinkedIn profile')
      a(href="https://github.com/JuanEstenbanQuirama" target="_blank")  
        img.icon(src='../assets/image/github.png' alt='My Github profile')
</template>

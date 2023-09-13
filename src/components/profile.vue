<template lang="pug">
section#profile
  .section__pic-container
    img(src='../assets/image/profile.jpeg' alt='juan profile picture')
  .section__text
    p.section__text__p1 Hello, I&apos;m
    h1.title Juan Esteban
    p.section__text__p2 Frontend Developer
    .btn-container
      button.btn.btn-color-2(onclick="window.open('./assets/resume-example.pdf')")
        | Download CV
      button.btn.btn-color-1(onclick="location.href='./#contact'")
        | Contact Info
    #socials-container
      img.icon(src='./assets/linkedin.png' alt='My LinkedIn profile' onclick="location.href='https://linkedin.com/'")
      img.icon(src='./assets/github.png' alt='My Github profile' onclick="location.href='https://github.com/'")
        

</template>

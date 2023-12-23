<template lang="pug">
section#contact
  p.section__text__p1 Get in Touch
  h1.title Contact Me
    form.contact-info-upper-container(action="https://formsubmit.co/jquiramadev@outlook.com" method="POST")
      input.contact-info-upper-container-input(type="text" placeholder="Name" name="name")
      input.contact-info-upper-container-input(type="email" placeholder="Email" name="email")
      input.contact-info-upper-container-input(type="text" placeholder="Subject" name="subjet")
      textarea.contact-info-upper-container-input(placeholder="Comments" cols="15" rows="5" name="comments")
      button.contact-info-upper-container-btn(type="submit") Send 
footer
  nav
    .nav-links-container
      ul.nav-links
        li
          a(href='#about') About
        li
          a(href='#experience') Experience
        li
          a(href='#projects') Projects
        li
          a(href='#contact') Contact
  p Copyright &copy; 2023 Dev Bitan. All Rights Reserved.
</template>
<!-- pendiente contacto, dejar correo y wtp, pero bien hechos -->
<!-- Organizar responsive -->
<!-- pendiente hja de vida que se pueda descargar  -->

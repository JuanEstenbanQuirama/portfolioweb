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
</template>


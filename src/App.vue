<script setup>
import navBar from './components/navBar.vue';
import profile from './components/profile.vue';
import about from './components/about.vue';
import experience from './components/experience.vue';
import projects from './components/projects.vue';
import contact from './components/contact.vue';
</script> 

<template lang="pug">
navBar
profile
about
experience
projects
contact
<canvas id="canvas"></canvas>

a(href="https://api.whatsapp.com/send?phone=573059052091" class="buymeacoffee" target="_blank" rel="noopener noreferrer")
    img.icon(src='././assets/image/whatsapp.png' alt='Education icon')

</template>

<style lang="scss">
body,
html {
  margin: 0px;
  padding: 0px;
//   position: fixed;
//   background: black;
}


.buymeacoffee {
  text-decoration: none;
  position: fixed;
  right: 2rem;
  bottom: 2rem;
  background: #FFDD00;
  width: 3.5rem;
  height: 3.5rem;
  border-radius: 50%;
  transition: all 0.1s linear;
  box-shadow: 0.2rem 0.2rem 0.5rem rgba(0, 0, 0, 0.2);
  z-index: 1000;
  display: flex;
  align-items: center;
  justify-content: center;
}

.buymeacoffee:hover {
  width: 4rem;
  height: 4rem;
  line-height: 4rem;
}

</style>


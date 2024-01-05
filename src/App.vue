<script setup>
import navBar from './components/navBar.vue';
import profile from './components/profile.vue';
import about from './components/about.vue';
import experience from './components/experience.vue';
import projects from './components/projects.vue';
import contact from './components/contact.vue';
import projectsView from './components/projectsView.vue';
</script> 

<template lang="pug">
navBar
profile
about
experience
projects
//- projectsView
contact
a(href="https://api.whatsapp.com/send?phone=573059052091" class="buymeacoffee" target="_blank" rel="noopener noreferrer")
    img.icon(src='././assets/image/whatsapp.png' alt='wtp icon')
</template>



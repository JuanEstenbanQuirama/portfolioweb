<script setup>
const toggleMenu = () => {
  const menu = document.querySelector(".menu-links");
  const icon = document.querySelector(".hamburger-icon");
  menu.classList.toggle("open");
  icon.classList.toggle("open");
};

const toggleTheme = () => {
  const buton = document.querySelector(".buttonChange");
  document.body.classList.toggle("dark");
  buton.classList.toggle("changeBtn");
};
</script>

<template lang="pug">
.toggleBk
  .toggleBkItem 
    input.inputDarkMode(type="checkbox" id="dark-mode")
    label.labelDarkMode(for="dark-mode" @click='toggleTheme()')
  nav#desktop-nav
    .logo-name
      div.logo-name Dev Bitan
    div
      ul.nav-links
        li
          a(href='#about') About
        li
          a(href='#experience') Experience
        li
          a(href='#projects') Projects
        li
          a(href='#contact') Contact
  nav#hamburger-nav
    .logo-name 
      .logo-name Dev Bitan
    .hamburger-menu
      .hamburger-icon(@click='toggleMenu()')
        span
        span
        span
      .menu-links
        li
          a(href='#about' @click='toggleMenu()') About
        li
          a(href='#experience' @click='toggleMenu()') Experience
        li
          a(href='#projects' @click='toggleMenu()') Projects
        li
          a(href='#contact' @click='toggleMenu()') Contact
</template>

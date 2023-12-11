<script setup>
const toggleMenu = () => {
  console.log("xd");
  const menu = document.querySelector(".menu-links");
  const icon = document.querySelector(".hamburger-icon");
  menu.classList.toggle("open");
  icon.classList.toggle("open");
};
</script>
<template lang="pug">
nav#desktop-nav
  .logo Dev Bitan
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
  .logo Dev Bitan
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

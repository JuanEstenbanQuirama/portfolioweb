
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
    .hamburger-icon(onclick='toggleMenu()')
      span
      span
      span
    .menu-links
      li
        a(href='#about' onclick='toggleMenu()') About
      li
        a(href='#experience' onclick='toggleMenu()') Experience
      li
        a(href='#projects' onclick='toggleMenu()') Projects
      li
        a(href='#contact' onclick='toggleMenu()') Contact
</template>
<!-- pendiente funcion para el menu hamburguesa -->
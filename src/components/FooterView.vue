<template lang="pug">
footer 
    nav.navfooter
        
        #socials-container
            a(href="https://www.linkedin.com/in/jquirama-dev-bitan/" target="_blank")
                img.icon(src='../assets/image/linkedin.png' alt='My LinkedIn profile')
            a(href="https://github.com/" target="_blank")  
                img.icon(src='../assets/image/github.png' alt='My Github profile')
        ul.nav-links
            li
            a(href='#about') About
            li
            a(href='#experience') Experience
            li
            a(href='#projects') Projects
            li
            a(href='#contact') Contact
    .btn-container-footer
        button.btn.btn-color-2
                a(href='/cvjuanestebanquiramalopez.pdf' target="_blank" download) Download CV
        button.btn.btn-color-1(onclick="location.href='./#contact'")
                | Contact Info
        p.emails Email: jquiramadev@outlook.com / jquirama96@gmail.com

    p Copyright &copy; 2023 Dev Bitan. All Rights Reserved.
</template>

<style lang="scss" scoped>
.btn-container-footer {
  display: flex;
  flex-direction: row;
//   height: 23vh;
  margin: 0 8.5rem;
  gap: 1rem;
  align-items: center;
  margin-bottom: 5vh;
}
.btn-container-footer-container {
    display: flex;
}

.navfooter {
    border-top: rgb(53, 53, 53) 0.1rem solid;
    box-shadow: rgba(0, 0, 0, 0.15) 7px -6px 2.6px;;
    border-radius: 10px;
    margin-top: 4vh;
}

.emails {
    padding: 0px 120px;
   
}
footer {
    margin-bottom: 5vh;
}

</style>

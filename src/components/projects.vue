<template lang="pug">
section#projects
  p.section__text__p1 Browse My Recent
  h1.title Projects
  .experience-details-container
    .about-containers
      .details-container.color-container
        .article-container
          img.project-img(src='../assets/image/bkit.png' alt='Project 3')
        h2.experience-sub-title.project-title Bikinifitness
        .btn-container
          a(href="https://github.com/" target="_blank")
            button.btn.btn-color-2.project-btn Github
          a(href="https://bikinifitnessclub.com/" target="_blank")
            button.btn.btn-color-2.project-btn Live Demo
      .details-container.color-container
        .article-container
          img.project-img(src='../assets/image/ddrop.png' alt='Project 1')
        h2.experience-sub-title.project-title Drag & Drop
        .btn-container
          a(href="https://github.com/JuanEstenbanQuirama/draganddrop" target="_blank")
            button.btn.btn-color-2.project-btn Github
          a(href="https://dragandadropdevbitan.netlify.app/" target="_blank")
            button.btn.btn-color-2.project-btn Live Demo
      .details-container.color-container
        .article-container
          img.project-img(src='../assets/image/tictactoe.png' alt='Project 2')
        h2.experience-sub-title.project-title Tic-tac-toe
        .btn-container
          a(href="https://github.com/JuanEstenbanQuirama/tictactoe" target="_blank")
            button.btn.btn-color-2.project-btn Github
          a(href="https://tictactocbydevbitan.netlify.app/" target="_blank")
            button.btn.btn-color-2.project-btn Live Demo
      
      //- .details-container.color-container
      //-   .article-container
      //-     img.project-img(src='../assets/image/tobbias.jpeg' alt='Project 3')
      //-   h2.experience-sub-title.project-title Project Three
      //-   .btn-container
      //-     button.btn.btn-color-2.project-btn(onclick="location.href='https://github.com/'")
      //-       | Github
      //-     button.btn.btn-color-2.project-btn(onclick="location.href='https://github.com/'")
      //-       | Live Demo
  img.icon.arrow(src='../assets/image/arrow-down.png' alt='Arrow icon' onclick="location.href='./#contact'")
    
</template>

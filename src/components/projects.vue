<template lang="pug">
section#projects
  p.section__text__p1 Browse My Recent
  h1.title Projects
  .experience-details-container
    .about-containers
      .details-container.color-container
        .article-container
          img.project-img(src='./assets/project-1.png' alt='Project 1')
        h2.experience-sub-title.project-title Project One
        .btn-container
          button.btn.btn-color-2.project-btn(onclick="location.href='https://github.com/'")
            | Github
          button.btn.btn-color-2.project-btn(onclick="location.href='https://github.com/'")
            | Live Demo
      .details-container.color-container
        .article-container
          img.project-img(src='./assets/project-2.png' alt='Project 2')
        h2.experience-sub-title.project-title Project Two
        .btn-container
          button.btn.btn-color-2.project-btn(onclick="location.href='https://github.com/'")
            | Github
          button.btn.btn-color-2.project-btn(onclick="location.href='https://github.com/'")
            | Live Demo
      .details-container.color-container
        .article-container
          img.project-img(src='./assets/project-3.png' alt='Project 3')
        h2.experience-sub-title.project-title Project Three
        .btn-container
          button.btn.btn-color-2.project-btn(onclick="location.href='https://github.com/'")
            | Github
          button.btn.btn-color-2.project-btn(onclick="location.href='https://github.com/'")
            | Live Demo
  img.icon.arrow(src='./assets/arrow.png' alt='Arrow icon' onclick="location.href='./#projects'")
    
</template>

<template lang="pug">
section#about
  p.section__text__p1 Get To Know More
  h1.title About Me
  .section-container
    .section__pic-container
      img.about-pic(src='../assets/image/profile2.jpeg' alt='Profile picture')
    .about-details-container
      .about-containers
        .details-container
          img.icon(src='../assets/image/experience.png' alt='Experience icon')
          h3 Experience
          p
            | 8+ months
            br
            | Frontend Development
        .details-container
          img.icon(src='../assets/image/education.png' alt='Education icon')
          h3 Education
          p
            | Front-end Development
            br
            | School of tehcnology and computer science
      .text-container
        p Desarrollador web Front end con conocimientos en HTML, CSS, Javascript y React. Soy decidido, versátil y capaz de simultanear varias tareas. Con amplia experiencia en entornos laborales en los que se valora el compromiso y la capacidad de trabajar en equipo. Me caracterizo por mi dinamismo, proactividad y entusiasmo; me interesa y estoy en constante aprendizaje de buenas prácticas, lenguajes y tecnologías para mejorar mis habilidades
          
  img.icon.arrow(src='../assets/image/arrow-down.png' alt='Arrow icon' onclick="location.href='./#experience'")

</template>

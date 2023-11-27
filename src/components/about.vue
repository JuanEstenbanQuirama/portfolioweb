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
            | 6+ months
            br
            | Frontend Development
        .details-container
          img.icon(src='../assets/image/education.png' alt='Education icon')
          h3 Education
          p
            | Front-end Development
            br
            | School of tehcnology and computer science - ACADEMLO
      .text-container
        p I am a passionate junior full-stack web developer with six months of experience, focused on being versatile and able to manage multiple tasks simultaneously. My background includes work environments that value commitment and teamwork. I am characterized by my dynamism, proactivity and enthusiasm. I am constantly looking for opportunities to learn and improve my skills, exploring best practices, languages and technologies. My experience has given me a solid foundation and I am eager to continue growing professionally.
  img.icon.arrow(src='../assets/image/arrow-down.png' alt='Arrow icon' onclick="location.href='./#experience'")

</template>

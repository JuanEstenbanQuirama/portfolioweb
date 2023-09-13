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
          img.icon(src='./assets/experience.png' alt='Experience icon')
          h3 Experience
          p
            | 2+ years 
            br
            | Frontend Development
        .details-container
          img.icon(src='./assets/education.png' alt='Education icon')
          h3 Education
          p
            | B.Sc. Bachelors Degree
            br
            | M.Sc. Masters Degree
      .text-container
        p
          | Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic quis
          | reprehenderit et laborum, rem, dolore eum quod voluptate
          | exercitationem nobis, nihil esse debitis maxime facere minus sint
          | delectus velit in eos quo officiis explicabo deleniti dignissimos.
          | Eligendi illum libero dolorum cum laboriosam corrupti quidem,
          | reiciendis ea magnam? Nulla, impedit fuga!
  img.icon.arrow(src='./assets/arrow.png' alt='Arrow icon' onclick="location.href='./#experience'")

</template>

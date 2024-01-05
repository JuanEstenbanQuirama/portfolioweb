<template lang="pug">
div.projectos#projects
  p.section__text__p1 Browse My Recent
  h1.title Projects
  .container
    div.container-cartas
      .card.card0
        .border 
            h2 BikiniFitness Club
            .icon
              a(href="https://github.com/" target="_blank")
                button.btn.btn-color-2.project-btn Github
              a(href="https://bikinifitnessclub.com/" target="_blank")
                button.btn.btn-color-2.project-btn Live Demo
      div.tecnologias Technologies: 
        img.imgtecno(src="../assets/image/code.svg")
        img.imgtecno(src="../assets/image/html.svg")
        img.imgtecno(src="../assets/image/javascript.svg")
        img.imgtecno(src="../assets/image/vuejs.svg")
        img.imgtecno(src="../assets/image/css.svg")
        img.imgtecno(src="../assets/image/sass.svg")
    div.container-cartas
      .card.card1
        .border 
            h2 Tictac-Toe
            .icon
              a(href="https://github.com/JuanEstenbanQuirama/tictactoe" target="_blank")
                button.btn.btn-color-2.project-btn Github
              a(href="https://tictactocbydevbitan.netlify.app/" target="_blank")
                button.btn.btn-color-2.project-btn Live Demo
      div.tecnologias Technologies: 
        img.imgtecno(src="../assets/image/code.svg")
        img.imgtecno(src="../assets/image/html.svg")
        img.imgtecno(src="../assets/image/typescript.svg")
        img.imgtecno(src="../assets/image/vuejs.svg")
        img.imgtecno(src="../assets/image/css.svg")
        img.imgtecno(src="../assets/image/sass.svg")
    div.container-cartas
      .card.card2
        .border 
            h2 Drag& Drop
            .icon
              a(href="https://github.com/JuanEstenbanQuirama/draganddrop" target="_blank")
                button.btn.btn-color-2.project-btn Github
              a(href="https://dragandadropdevbitan.netlify.app/" target="_blank")
                button.btn.btn-color-2.project-btn Live Demo
      div.tecnologias Technologies: 
        img.imgtecno(src="../assets/image/code.svg")
        img.imgtecno(src="../assets/image/html.svg")
        img.imgtecno(src="../assets/image/javascript.svg")
        img.imgtecno(src="../assets/image/vuejs.svg")
        img.imgtecno(src="../assets/image/css.svg")
        img.imgtecno(src="../assets/image/sass.svg")
    div.container-cartas
      .card.card3
        .border 
            h2 Pokemon search
            .icon
              a(href="https://github.com/JuanEstenbanQuirama/PokedexaApi" target="_blank")
                button.btn.btn-color-2.project-btn Github
              a(href="https://pokeapiapp.netlify.app/" target="_blank")
                button.btn.btn-color-2.project-btn Live Demo
      div.tecnologias Technologies: 
        img.imgtecno(src="../assets/image/code.svg")
        img.imgtecno(src="../assets/image/html.svg")
        img.imgtecno(src="../assets/image/javascript.svg")
        img.imgtecno(src="../assets/image/react.svg")
        img.imgtecno(src="../assets/image/css.svg")
        img.imgtecno(src="../assets/image/sass.svg")
  //- img.arrow(src='../assets/image/arrow-down.png' alt='Arrow icon' onclick="location.href='./#contact'")
    
</template>

<style lang="scss" scoped>
.container {
  padding: 0 20px;
  min-height: fit-content;
  max-width: 800px;
  margin: 0 auto;
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 2rem;
}
.tecnologias {
  border: rgb(53, 53, 53) 0.1rem solid;
  border-color: rgb(163, 163, 163);
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
  border-radius: 12px;
  padding: 12px;
  font-weight: 900;
  width: 300px;
  margin: 0 auto;
  display: flex;
    gap: .3rem;
}
.container-cartas {
  display: flex;
  flex-direction: column;
  // align-items: center;
  justify-content: center;
}

.border {
  position: relative;
  height: 342px;
  width: 260px;
  background: transparent;
  border-radius: 12px;
  border: 2px solid white;
  opacity: 0;
  transition: 1s ease;
}

.border:hover {
  opacity: 1;
}

.card {
  position: relative;
  height: 379px;
  max-width: 300px;
  width: 100%;
  background: #808080;
  margin: 16px 30px;
  border-radius: 15px;
  transition: 0.8s ease;
  overflow: hidden;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
  display: flex;
  justify-content: center;
  align-items: center;
  cursor: pointer;
}

.card0 {
  background: url(../assets/image/bkit.png) center center no-repeat;
  background-size: 350px;
  
}
.card0:hover {
  background: url(../assets/image/bkit.png) left center no-repeat;
  background-size: 600px;
}

.card1 {
  background: url(../assets/image/tictac.png) center center no-repeat;
  background-size: 350px;
}
.card1:hover {
  background: url(../assets/image/tictac.png) left center no-repeat;
  background-size: 600px;
}

.card2 {
  background: url(../assets/image/ddrop.png) center center no-repeat;
  background-size: 350px;
}
.card2:hover {
  background: url(../assets/image/ddrop.png) left center no-repeat;
  background-size: 600px;
}

.card3 {
  background: url(../assets/image/pokedex.png) center center no-repeat;
  background-size: 350px;
}
.card3:hover {
  background: url(../assets/image/pokedex.png) left center no-repeat;
  background-size: 600px;
}

h2 {
  position: absolute;
  bottom: 130px;
  left: 25px;
  width: 15px;
  color: #fff;
  font-size: 30px;
  line-height: 1.1em;
  text-shadow: 0 0 10px rgba(0, 0, 0, 0.5);
}

.icon {
  position: absolute;
  color: #fff;
  height: 100px;
  bottom: 18px;
  display: flex;
  left: 25px;
  flex-direction: column;
  align-items: start;
  justify-content: center;
  gap: 1rem;
}

span {
  // font-size: 20px;
  transition: 0.2 ease;
}
span:hover {
  font-size: 22px;
  color: white;
  transition: 0.2 ease;
}

.imgtecno {
  width: 22px;

  
}
</style>


<template lang="pug">
section
.container
    .card.card0
        .border 
            h2 BikiniFitness Club
            .icon
                span Github 
                span Live demo  
                span Tecnolies
    .card.card1
        .border 
            h2 tic tac toe
            .icon
                span Github 
                span Live demo 
                span Tecnolies
.container
    .card.card2
        .border 
            h2 drag and drop
            .icon
                span Github 
                span Live demo 
                span Tecnolies
    .card.card3
        .border 
            h2 search pokemon
            .icon
                span Github 
                span Live demo  
                span Tecnolies

</template>

<style lang="scss" scoped>
.container {
  padding: 0 20px;
  min-height: fit-content;
  max-width: 800px;
  min-width: 600px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 auto;
}

.border {
  position: relative;
  height: 342px;
  width: 260px;
  background: transparent;
  border-radius: 12px;
  border: 2px solid tomato;
  opacity: 0;
  transition: 1s ease;
}

.border:hover {
  opacity: 1;
}

.card {
  position: relative;
  height: 379px;
  width: 300px;
  background: #808080;
  margin: 30px;
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
  background: url(../assets/image/tictac.png) center center no-repeat;
  background-size: 300px;
}
.card0:hover {
  background: url(../assets/image/tictac.png) left center no-repeat;
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
  bottom: 30px;
  display: flex;
  left: 25px;
  flex-direction: column;
  align-items: start;
  justify-content: center;
}

span {
  // font-size: 20px;
  transition: 0.2 ease;
}
span:hover {
  font-size: 20px;
  color: red;
  transition: 0.2 ease;
}
</style>

<template>
  <div class="principal">
    <header class="header-page"></header>
    <section class="inicial">
      <h3 class="subtitle">Para o cuidado de todo Pet</h3>
      <h1 class="title">Cat-Dog-Mimo</h1>
    </section>

    <section class="second">
      <div class="grid">
        <div id="box-1" class="grid-item">
          <h1>Limpe tudo em volta dos animais de estimação</h1>
          <img src="../assets/seta.png" alt="" />
        </div>
        <div id="box-2" class="grid-item">
          <img src="../assets/pet.png" alt="" />
          <p>Lorem, ipsum dolor sit amet consectetur</p>
        </div>

        <div id="box-3" class="grid-item"></div>

        <div id="box-4" class="grid-item">
          <img src="../assets/dog.png" alt="" />
          <p>Lorem, ipsum dolor sit amet consectetur</p>
        </div>

        <div id="box-5" class="grid-item"></div>

        <div id="box-6" class="grid-item">
          <img src="../assets/cat.png" alt="" />
          <p>Lorem, ipsum dolor sit amet consectetur</p>
        </div>
      </div>
    </section>

    <section class="terceiro">
      <Cat />
    </section>

    <footer class="footer-page"></footer>
  </div>
</template>

<script>
import Cat from "./Cat";

export default {
  name: "DogCat",
  components: {
    Cat,
  },
};
</script>

<style scoped>
.principal {
  background-image: url(../assets/dog-space.jpeg);
  background-size: cover;
  background-position: center center;
  background-attachment: fixed;
  background-repeat: no-repeat;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: 100vw;

  align-items: center;
}

.inicial {
  /* perspective: 10px; */
  display: flex;
  align-items: center;
  flex-direction: column;
  background-image: url(../assets/dog.jpeg);
  background-size: cover;
  background-position: center right;
  /* transform: scale(1 ,1 ); */
  /* background-size:98vw 100vh ; */

  background-repeat: no-repeat;
  width: 71vw;
  height: 100vh;
}

.second {
  overflow-x: hidden;
  background-color: #fff;
  width: 71vw;
  height: 100vh;
}

.grid {
  height: 100vh;
  justify-content: center;
  align-content: center;
  display: grid;
  grid-template-columns: 18vw 18vw 18vw;
  grid-template-rows: 35vh 35vh;
}

.grid-item {
  background-color: rgba(255, 255, 255, 0.8);
  text-align: center;
  padding: 20px 0;
  font-size: 30px;
}

#box-1 {
  background-color: black;
  display: flex;
  align-content: center;
  justify-content: space-around;
  flex-direction: column;
}
#box-2 {
  background-color: #ffffff;
}
#box-3 {
  background-image: url(../assets/human-dog.jpeg);
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
}
#box-4 {
  background-color: #ffffff;
}
#box-5 {
  background-image: url(../assets/pet-dog.jpeg);
  background-size: cover;
  background-position: center center;
  
  background-repeat: no-repeat;
}
#box-6 {
  background-color: #fff;
}

#box-1 > h1 {
  font-weight: 100;
  padding: 10px;
  color: #fff;
  text-align: start;
  font-size: 15pt;
  font-family: "Playfair Display", serif;
}

#box-1 > img {
  background-color: #fff;
  border-radius: 15px;
  width: 20%;
  margin-left: 1vw;
}

#box-2 > img {
  width: 20%;
}

#box-2 > p {
  font-size: 16pt;
  font-family: "roboto", serif;
}

#box-4 > img {
  width: 20%;
}

#box-4 > p {
  font-size: 16pt;
  font-family: "roboto", serif;
}

#box-6 > img {
  width: 20%;
}

#box-6 > p {
  font-size: 16pt;
  font-family: "roboto", serif;
}

.header-page {
  background-color: black;
  width: 100vw;
  height: 5vh;
}

.footer-page {
  background-color: black;
  width: 100vw;
  height: 5vh;
}

.title {
  font-weight: 100;
  font-size: 40pt;
  font-family: "Playfair Display", serif;
}

.subtitle {
  letter-spacing: 4px;
  font-family: "Roboto", sans-serif;
  margin-top: 15vh;
}

/* @media screen and (min-width: 320px)  {
  .inicial {
  background-image: url(../assets/dog.jpeg);
  background-size: 100% 80%;
  background-repeat: no-repeat;
  width: 100vw;
  height: 100vh;
}
} */
</style>

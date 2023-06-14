<template>
  <div class="principal">
    <header class="header-page"></header>
    <section class="inicial">
      <h3 class="subtitle">Para o cuidado de todo Pet</h3>
      <h1 class="title">Cat-Dog-Mimo</h1>
    </section>

    <section data-aos-delay="1020" data-aos="fade-left" class="second">
      <SecondPage />
    </section>

    <section data-aos-delay="1020" data-aos="fade-right" class="terceiro">
      <Cat />
    </section>

    <FourthPage data-aos-delay="1020" data-aos="fade-up-left" />

    <section data-aos-delay="1020" data-aos="fade-down" class="last-page">
      <LastPage />
    </section>

    <footer class="footer-page"></footer>
  </div>
</template>



<script >
import Cat from "./Cat";
import FourthPage from "./FourthPage.vue";
import LastPage from "./LastPage.vue";
import SecondPage from "./SecondPage.vue";

export default {
  name: "DogCat",
  components: {
    Cat,
    FourthPage,
    LastPage,
    SecondPage
  },
};
</script>

<style scoped>
.principal {
  background-image: url(../assets/horizonte.jpg);
  background-size: cover;
  background-position: 0vw 0vh;
  background-attachment: fixed;
  background-repeat: no-repeat;
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  width: 100vw;

  align-items: center;
}

.inicial {
  box-shadow: #000000 1px 2px 10px 1px;
  /* perspective: 10px; */
  display: flex;
  align-items: center;
  flex-direction: column;
  background-image: url(../assets/dog.jpeg);
  background-size: cover;
  background-position: 0vw 0vh;
  /* transform: scale(1 ,1 ); */
  /* background-size:98vw 100vh ; */

  background-repeat: no-repeat;
  width: 71vw;
  height: 100vh;
}

.second {
  box-shadow: #000000 1px 2px 10px 1px;
  overflow-x: hidden;
  background-color: #fff;
  width: 71vw;
  height: 100vh;
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

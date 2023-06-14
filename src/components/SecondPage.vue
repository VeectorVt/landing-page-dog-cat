<template>
  <div class="grid">
    <div data-aos-delay="3000" data-aos="zoom-in" id="box-1" class="grid-item">
      <h1>Limpe tudo em volta dos animais de estimação</h1>
      <img src="../assets/seta.png" alt="" />
    </div>
    <div data-aos-delay="3000" data-aos="zoom-in" id="box-2" class="grid-item">
      <img src="../assets/pet.png" alt="" />
      <p>Lorem, ipsum dolor sit amet consectetur</p>
    </div>

    <div
      data-aos-delay="3000"
      data-aos="zoom-in"
      id="box-3"
      class="grid-item"
    ></div>

    <div data-aos-delay="3000" data-aos="zoom-in" id="box-4" class="grid-item">
      <img src="../assets/dog.png" alt="" />
      <p>Lorem, ipsum dolor sit amet consectetur</p>
    </div>

    <div
      data-aos-delay="3000"
      data-aos="zoom-in"
      id="box-5"
      class="grid-item"
    ></div>

    <div data-aos-delay="3000" data-aos="zoom-in" id="box-6" class="grid-item">
      <img src="../assets/cat.png" alt="" />
      <p>Lorem, ipsum dolor sit amet consectetur</p>
    </div>
  </div>
</template>


<script>
export default {
  name: "Second Page",
};
</script>

<style scoped>
.grid {
  height: 100vh;
  justify-content: center;
  align-content: center;
  display: grid;

  grid-template-columns: 18vw 18vw 18vw;
  grid-template-rows: 35vh 35vh;
}

.grid-item {
  box-shadow: #000 1px 2px 10px 1px;
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
  transition: 0.5s;
}

#box-1:hover {
  transform: scale(1.2, 1.2);
  box-shadow: none;
  border-radius: 10px;
  z-index: 999;
}
#box-2 {
  background-color: #ffffff;
  transition: 0.5s;
}
#box-2:hover {
  transform: scale(1.2, 1.2);
  box-shadow: none;
  border-radius: 10px;
  border: 2px dashed black;
  z-index: 999;
}

#box-3 {
  background-image: url(../assets/human-dog.jpeg);
  background-size: cover;
  background-position: center center;
  background-repeat: no-repeat;
  transition: 0.5s;
}
#box-3:hover {
  transform: scale(1.2, 1.2);
  box-shadow: none;
  border-radius: 10px;
  border: 2px dashed black;
  z-index: 999;
}
#box-4 {
  background-color: #ffffff;
  transition: 0.5s;
}
#box-4:hover {
  transform: scale(1.2, 1.2);
  box-shadow: none;
  border-radius: 10px;
  border: 2px dashed black;
  z-index: 999;
}
#box-5 {
  background-image: url(../assets/pet-dog.jpeg);
  background-size: cover;
  background-position: center center;
  transition: 0.5s;
  background-repeat: no-repeat;
}
#box-5:hover {
  transform: scale(1.2, 1.2);
  box-shadow: none;
  border-radius: 10px;
  border: 2px dashed black;
  z-index: 999;
}
#box-6 {
  background-color: #fff;
  transition: 0.5s;
}
#box-6:hover {
  transform: scale(1.2, 1.2);
  box-shadow: none;
  border-radius: 10px;
  border: 2px dashed black;
  z-index: 999;
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
  transition: 0.5s;
}
#box-1 > img:hover {
  transform: scaleX(0.5);
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
</style>

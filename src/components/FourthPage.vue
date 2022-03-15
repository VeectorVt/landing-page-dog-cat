<template>
  <section class="fourth-page">
    <div class="primary">
      <div class="text">
        <h2>VET CLINIC</h2>
        <h1>Rescue a Pet</h1>
        <p>
          Lorem ipsum dolor sit Lorem ipsum dolor sit amet consectetur
          adipisicin
        </p>
      </div>
      <div class="images">
        <div class="image-dog"></div>
        <div class="image-bear"></div>
      </div>
    </div>
    <div class="second">
      <div class="text-second">
        <h2>DOG TRAINING</h2>
        <h1>We use humane, natural, dog  training methods</h1>
      </div>
      <div class="images-second">
        <div class="image-dog-white"></div>
        <div class="text-div">
          <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Quod accusantium iusto labore at, tenetur corporis saepe necessitatibus, optio neque alias sequi rem, voluptatibus ipsa dignissimos debitis repellat illum explicabo in?</p>
        </div>
      </div>
    </div>
  </section>
</template>


<script>
export default {
  name: "FourthPage",
};
</script>

<style scoped>
.fourth-page {
  display: flex;
  flex-direction: column;
  justify-content: space-around;
  background-color: #e5e5e5;
  box-shadow: #000 1px 2px 10px 1px;
  width: 71vw;
  height: 180vh;
}

.primary {
  display: flex;
  flex-direction: row;
  justify-content: left;
  align-content: left;
  width: 71vw;
  height: 60vh;
}

.second {
  display: flex;
  flex-direction: row;
  justify-content: left;
  align-content: left;
  width: 71vw;
  height: 80vh;
}

.text {
  width: 30vw;
}

.text-second {
  width: 30vw;
  margin-top: 30vh;
}

.text-second > h1 {
  text-align: right;
  width: 23vw;
  margin-left: 3vw;
  font-size: 27pt;
}

h1 {
  font-weight: 100;
  padding: 10px;
  color: rgb(0, 0, 0);
  text-align: start;
  font-size: 27pt;
  font-family: "Playfair Display", serif;
  margin-left: 5vw;
}

h2 {
  font-weight: 700;
  padding: 10px;
  color: rgb(0, 0, 0);
  font-size: 16pt;
  font-family: "roboto", serif;
  letter-spacing: 10px;
  margin-top: 10vh;
  margin-left: 5vw;
}

p {
  font-weight: 500;
  padding: 10px;
  color: rgb(0, 0, 0);
  font-size: 12pt;
  font-family: "roboto", serif;
  margin-left: 5vw;
}

.images {
  display: flex;
  margin-right: 5vw;
  width: 43vw;
  height: 80vh;
  box-shadow: #000 1px 2px 10px 1px;
}

.images-second {
  margin-top: 10vh;
 
  display: flex;
  width: 43vw;
  height: 80vh;
  box-shadow: #000 1px 2px 10px 1px;
}

.image-dog {
  width: 30vw;
  height: 80vh;
  background-image: url(../assets/image-dog.jpeg);
  background-size: cover;
  /* background-size:80vw 100vh ; */
  background-repeat: no-repeat;
}
.image-bear {
  width: 25vw;
  height: 80vh;
  background-image: url(../assets/555.png);
  background-color: black;
  background-size: contain;
  background-position: 0vw 50vh;
  background-repeat: no-repeat;
}
.image-dog-white{
  width: 25vw;
  height: 80vh;
  background-image: url(../assets/dog-white.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
}
.text-div{
  font-size: 37pt;
  display: flex;
  flex-direction: row;
  justify-content: center;
  align-items: center;
  width: 20vw;
  background-color: #fff;
}

.text-div > p{
  font-weight: 400;
  margin-left: 1vw;
  margin-right: 1vw;
  text-align: left;
  font-size: 12pt;
  line-height: 4.5vh;
}
</style>

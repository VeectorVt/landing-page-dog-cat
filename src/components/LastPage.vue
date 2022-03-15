<template>
  <div class="last-page">
    <div class="text-div">
      <h1>Basic Dog</h1>
      <h2>TRAINING</h2>
      <p>
        Lorem ipsum, dolor sit amet consectetur adipisicing elit. Consequatur
        consequuntur facere quam iste
      </p>
      <button id="button" type="button" >Ler Mais</button>
    </div>
  </div>
</template>


<script>
export default {
  name: "LastPage",
};
</script>

<style scoped>
.last-page {
  box-shadow: #000000 1px 2px 10px 1px;
  display: flex;
  flex-direction: column;
  justify-content: left;
  align-content: center;
  width: 71vw;
  height: 100vh;
  background-image: url(../assets/dog-training.jpg);
  background-size: cover;
  background-position: 0vw 0vh;
  /* background-size:80vw 100vh ; */
  background-repeat: no-repeat;
}

.text-div > h1 {
  font-weight: 100;
  padding: 10px;
  color: rgb(0, 0, 0);
  text-align: start;
  font-size: 27pt;
  font-family: "Playfair Display", serif;
  margin-top: 10vh;
  margin-left: 5vw;
}

.text-div > h2 {
  font-weight: 700;
  padding: 10px;
  color: rgb(0, 0, 0);
  font-size: 16pt;
  font-family: "roboto", serif;
  letter-spacing: 10px;
  margin-left: 5vw;
}

.text-div {
  font-size: 37pt;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: flex-start;
  width: 30vw;
}

.text-div > p {
  font-family: "roboto", serif;
  font-weight: 400;
  margin-left: 6vw;
  text-align: left;
  font-size: 0.37em;
  line-height: 4.5vh;
}

#button{
  border: none;
  font-weight: 900;
    letter-spacing: 3px;
  font-size: 0.4em;
  font-family: "roboto", serif;
  color: white;
  background-color: #000000;
   margin-top: 4vh;
   margin-left: 6vw;
   width: 15vw;
   height: 8vh;
   transition: 0.5s;
}

#button:hover{
  
  cursor: pointer;
  opacity: 0.6;
}
</style>

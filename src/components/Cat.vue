<template>
  <div class="cat">
    <h1>
      Cat Stories, News, <br />
      Tips &amp; Tricks
    </h1>
    <h2>TIPS FOR LIFE WITH CATS</h2>
  </div>
</template>


<script>
export default {
  name: "Cat",
};
</script>

<style scoped>
.cat {
  display: flex;
  flex-direction: column;
  justify-content: left;
  align-content: center;
  width: 71vw;
  height: 100vh;
  background-image: url(../assets/cat-lend.jpeg);
  background-size: cover;
  /* background-size:80vw 100vh ; */
  background-repeat: no-repeat;
}

.cat > h1 {
  font-weight: 100;
  padding: 10px;
  color: rgb(255, 251, 251);
  text-align: start;
  font-size: 27pt;
  font-family: "Playfair Display", serif;
  margin-top: 10vh;
  margin-left: 5vw;
}

.cat > h2 {
  font-weight: 700;
  padding: 10px;
  color: #fff;
  font-size: 16pt;
  font-family: "roboto", serif;
  letter-spacing: 4px;
  margin-left: 5vw;
}
</style>

<template>
  <div class="hello">
    <div class="menu">
      <div class="menu-item menu-text">
        Resume
      </div>
      <div class="menu-item menu-text">
        Skating
      </div>
      <div class="menu-item menu-center">
        Neil Andrei
      </div>
      <div class="menu-item menu-text">
        Youtube
      </div>
      <div class="menu-item menu-text">
        About
      </div>
    </div>
    <div class="name">
      <div class="letter">
        <img src="../assets/img/3.png" class="img-responsive letter-image" alt="">
      </div>
      <div class="letter">
        <img src="../assets/img/3.png" class="img-responsive letter-image" alt="">
      </div>
      <div class="letter">
        <img src="../assets/img/3.png" class="img-responsive letter-image" alt="">
      </div>
      <div class="letter">
        <img src="../assets/img/3.png" class="img-responsive letter-image" alt="">
      </div>
      <div class="letter">
        <img src="../assets/img/3.png" class="img-responsive letter-image" alt="">
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
.name{
  display: flex;
  text-align: center;
  justify-content: center;
  vertical-align: middle;
  width: 100%;
  height: 100vw;
}
.letter{
  margin: .8%;
  filter: drop-shadow(0px 0px 7px rgba(150,150,150, .7));
  /*max-width: 25%;*/
}
.letter-image{
  width: 100%;
}
.menu{
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 10px;
}
.menu-item{
  flex: 1;
  text-align: center;
}
.menu-text{
  font-size: 20px;
  color: #818181;
  cursor: pointer;
  padding: 10px;
  border-bottom: 2px solid #080808;
  width: fit-content;
}
.menu-text:hover{
  /*color: #c278ff;*/
  border-bottom: 2px solid #c278ff;
}
.menu-center{
  font-size: 36px;
  color:#EAEAEA;
}
</style>

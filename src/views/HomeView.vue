<template>
  <div class="main-wrapper">
  <div class="bg">
    <Navigation/>
   <div class="header">
      <h1>I am Yonas Sisay</h1>
    <h2>Fullstack Developer</h2>
      <hr>
  <Social/>
      
   </div>
</div>
</div>
</template>

<script>
import Navigation from '../components/Nav.vue'
import Social from '../components/Socailmeda.vue'
  
export default {
  components:{
    Navigation,
    Social
  },

  
} 
</script>

<style scoped>
.bg{
  background-image: url(../assets/hero-bg.jpeg);
  background-size: cover;
  background-repeat: no-repeat;
  background-attachment: fixed;
  width: 100%;
  height: 100vh;
  display: flex;
  flex-direction: column;
  align-items: center;
}
hr{
  border: 1px dashed white;
}
.bg h1,h2{
  color: #fff;
  padding:2vh;
}
h1{
  font-size: 5rem;
  animation-name: textAnimation;
  animation-duration: 4s;
    animation-iteration-count: infinite;
    animation-delay: 2s;
    animation-direction: alternate-reverse;
    font-style: italic;

}


h2{
  font-size: 2.5rem;
  text-align: center;
  font-family: 'Montserrat', serif;
  font-weight: lighter;
  margin-top: 2vh;
}
.header{
  padding-top: 35vh;
}

@keyframes textAnimation {
   0%   {color:rgb(131, 101, 101); left:0px; top:0px;}
  25%  {color:rgb(128, 128, 51); left:20px; top:0px;}
  50%  {color:rgb(174, 189, 172); left:20px; top:20px;}
  75%  {color:rgb(106, 112, 117); left:0px; top:20px;}
  100% {color:rgb(190, 186, 186); left:0px; top:0px;}
}

</style>
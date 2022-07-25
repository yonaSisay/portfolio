<template>
  <div class="wrapper">
    <div class="nav" id="nav">
      <div class="left">
        <a href="#">JONAH</a>
      </div>
      <div class="right">
        <a href="#">About</a>
        <a href="#">Skill</a>
        <a href="#">Portfolio</a>
        <a href="#">Contact</a>
      </div>
    </div>
  </div>
</template>

<script>
  export default {};
</script>

<style scoped>
  .wrapper {
    width: 100%;
    display: flex;
    justify-content: center;
  }
  .nav {
    width: 80%;
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    padding-top: 8vh;
    position: fixed;
  }
  .wrapper .nav a {
    text-decoration: none;
    color: #fff;
    font-family: "Montserrat", serif;
    font-weight: 400;
    font-size: 1.5rem;
    display: inline-block;
    position: relative;
    opacity: 0.8;

  }
  .nav .right a {
    margin-left: 2vw;
  }
  .nav .left a {
    font-size: 2.5rem;
    font-style: oblique;
    font-weight: 500;
  }
  a:after {
    content: "";
    position: absolute;
    width: 100%;
    transform: scaleX(0);
    height: 2px;
    bottom: 0;
    left: 0;
    background-color: #fff;
    transform-origin: bottom right;
    transition: transform 0.25s ease-out;
  }
  a:hover::after {
    transform: scaleX(1);
    transform-origin: bottom left;
  }
</style>

<template>
  <div class="social-menu">
        <ul>
            <li><a href="https://github.com/sanketbodke" target="blank"><i class="fab fa-github"></i></a></li>
            <li><a href="https://www.instagram.com/imsanketbodke/" target="blank"><i class="fab fa-instagram"></i></a></li>
            <li><a href="https://www.linkedin.com/in/sanket-bodake-995b5b205/" target="blank"><i class="fab fa-linkedin-in"></i></a></li>
            <li><a href="https://codepen.io/sanketbodke"><i class="fab fa-codepen" target="blank"></i></a></li>
        </ul>
    </div>
</template>

<script>
export default {

}
</script>

<style>

.social-menu{
    padding-top: 10vh;
}
.social-menu ul{
    position: absolute;
    top: 90%;
    left: 50%;
    padding: 0;
    margin: 0;
    transform: translate(-50%, -50%);
    display: flex;
    /* flex-directio: column; */
}

.social-menu ul li{
    list-style: none;
    margin: 6px 15px;
}

.social-menu ul li .fab{
    font-size: 30px;
    line-height: 60px;
    transition: .3s;
    color: #000;
}

.social-menu ul li .fab:hover{
    color: #fff;
}

.social-menu ul li a{
    position: relative;
    display: block;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    background-color: #fff;
    text-align: center;
    transition: .6s;
    box-shadow: 0 5px 4px rgba(0,0,0,.5);
}

.social-menu ul li a:hover{
    transform: translate(0, -10%);
}

.social-menu ul li:nth-child(1) a:hover{
    background-color: rgba(0, 0, 0, 0.829);
}
.social-menu ul li:nth-child(2) a:hover{
    background-color: #E4405F;
}
.social-menu ul li:nth-child(3) a:hover{
    background-color: #0077b5;
}
.social-menu ul li:nth-child(4) a:hover{
    background-color: #000;
}
</style>
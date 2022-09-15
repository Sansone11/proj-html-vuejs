<template>
    <div class="header__wrapper">
        <div class="nav__bar">
            <div class="logo">
                <img src="../assets/img/logo-light.png" alt="">
            </div> 
            <ul class="menu">
                <li v-for="option in menu" :key="option" ><a  href="#">{{option}}</a></li>
            </ul>
            <ul class="menu__icon">
                <li><a href="#">#</a></li>
                <li><a href="#">#</a></li>
                <li><a href="#">#</a></li>
            </ul>

        </div>
        <div class="hero">
            <h1>Contemporany ideas</h1>
            <div class="text">
                <p>Lorem ipsum gravida nibh vel velit auctor aliquentean sollicitudin,lorem quis bibendum auci elit
                consequat</p>
                <p >ipsutis sem nibh id elited odio siy amet nibcursus a sit amet mauris.</p>
            </div>
            <button class="register"><a href="#">Register Now</a></button>
        </div>
        <ul class="circle__select">
            <li>
                <div class="circle"></div>
            </li>
            <li>
                <div class="circle"></div>
            </li>
            <li>
                <img src="../assets/img/interactive-map-slider-icon-close.png" alt="">
            </li>
        </ul>
        <div class="overlay">

        </div>
    </div>
</template>
  
<script>
export default {
    data(){
        return{
            menu: ['HOME','COURSES','INSTRUCTORS','EVENTS','PAGES','ELEMENTS']
        }
    }
}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import'../assets/Style.scss';

.header__wrapper {
    background-image: url(../assets/img/course-9-f-img.jpg);
    background-size: cover;
    background-position: center;
    min-height: 600px;
    padding-top: 30px;
    position: relative;
    text-align: center;
    width: 1200px;
    margin:0 auto;

    .overlay {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        // background-color: rgba($color: #000000, $alpha: 0.4);
    }

    .hero {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        min-height: 600px;
    }

    .menu{
        display: flex;
        gap: 3rem;
    }

    .register {
        height: 70px;
        width: 250px;
        color: white;
        background-color: $-register-button;
        border: none;
        margin-bottom: 15rem;
    }

    .register>a {
        text-decoration: none;
        color: white;
        font-weight: bold;
        
    }

    .text{
        margin-bottom: 40px;
    }

    .circle__select {
        display: flex;
        list-style: none;
        gap: 5px;
        position: absolute;
        bottom: 10px;
        right:48% ;
    }
    .circle{
        display: flex;
        height: 11px;
        width: 11px;
        border: solid 2px;
        border-radius: 50%;
        color:white;
       
       
    }

    .centre{
        align-self: center;
        justify-self: center;
        border: none;
    }
    .centre>img{
        width: 100%;
        height: 100%;
    }
}

.nav__bar {
    display: flex;
    justify-content: space-around;
    align-items: center;
    width: 100%;
    margin-top: 0;

    ul {
        list-style: none;
        display: flex;

    }

    .menu__icon {
        gap: 3rem;

    }

    li{
        gap: 3rem;
    }

    a {
        text-decoration: none;
        color: white;
    }
}

h1 {
    font-size: 100px;
    color: $-hero-write;
}

p {
    color: white;
    font-size: 25px;
}
</style>
  
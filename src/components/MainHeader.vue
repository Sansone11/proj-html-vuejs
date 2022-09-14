<template>
    <div class="header__wrapper">
        <div class="nav__bar">
            <div class="logo">
                <img src="../assets/img/logo-light.png" alt="">
            </div>
            <ul class="menu">
                <li><a href="#">HOME</a></li>
                <li><a href="#">COURSES</a></li>
                <li><a href="#">INSTRUCTORS</a></li>
                <li><a href="#">EVENTS</a></li>
                <li><a href="#">PAGES</a></li>
                <li><a href="#">ELEMENTS</a></li>
            </ul>
            <ul class="menu__icon">
                <li><a href="#">#</a></li>
                <li><a href="#">#</a></li>
                <li><a href="#">#</a></li>
            </ul>

        </div>
        <div class="hero">
            <h1>Contemporany ideas</h1>
            <p>Lorem ipsum gravida nibh vel velit auctor aliquentean sollicitudin,lorem quis bibendum auci elit
                consequat ipsutis sem nibh id elited odio siy amet nibcursus a sit amet mauris.</p>
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
                <div class="circle centre"><span id="point"></span></div>
            </li>
        </ul>
        <div class="overlay">

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

    .overlay {
        position: absolute;
        top: 0;
        bottom: 0;
        left: 0;
        right: 0;
        background-color: rgba($color: #000000, $alpha: 0.2);
    }

    .hero {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }

    .register {
        height: 50px;
        width: 200px;
        color: white;
        background-color: $-register-button;
        border: none;
    }

    .register>a {
        text-decoration: none;
        color: white;
        font-weight: bold;
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
        height: 12px;
        width: 12px;
        border: solid 2px;
        border-radius: 50%;
        color:white;
       
       
    }

    .centre{
        align-self: center;
        justify-self: center;
    }
    #point{
        height: 2px;
        width: 2px;
        border: solid 2px;
        background-color: white;
        border-radius: 50%;
        align-self: center;
        justify-self: center;
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

    .menu {
        gap: 3rem;
    }

    a {
        text-decoration: none;
        color: white;
    }
}

h1 {
    font-size: 60px;
    color: $-hero-write;
}

p {
    color: white;
    max-width: 780px;
    display: block;
    margin-bottom: 10px;
}
</style>
  
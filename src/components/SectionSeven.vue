<template>
    <div class="row">
        <div class="container">
            <h2>Pricing Plans</h2>
            <p class="sub__title">Lorem ipsum nibh vel velit auctor aliquentean sollicitudin,lorem quis bibendum auci</p>
            <div class="card__wrapper">
                <div class="card">
                    <div class="header">
                        <h3>Save up to 40% by payng weekly</h3>
                    </div>
                    <div>
                        <ul>
                            <li><a class="mat" href="#">Number of Courses</a></li>
                            <li><a class="mat" href="#">Time</a></li>
                            <li><a class="mat" href="#">Web Designing</a></li>
                            <li><a class="mat" href="#">Human-Centered Design</a></li>
                            <li><a class="mat" href="#">Basic Markrting</a></li>
                            <li><a class="mat" href="#">Python for Everybody</a></li>
                            <li><a class="mat" href="#">Android Developer</a></li>
                            <li><a class="mat" href="#">Business English</a></li>
                        </ul>

                    </div>
                </div>
                <div class="card">
                    <div class="header">
                        <img src="../assets/img/h5-custom-icon-7.png" alt="">
                        <h3>Standard</h3>
                        <p class="price">$12</p>
                    </div>
                    <div>
                        <ul>
                            <li>2</li>
                            <li><a class="mat" href="#">15 Days</a></li>
                            <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                            <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                            <li><a class="mat" href="#"><i class="fa-solid fa-xmark"></i></a></li>
                            <li><a class="mat" href="#"><i class="fa-solid fa-xmark"></i></a></li>
                            <li><a class="mat" href="#"><i class="fa-solid fa-xmark"></i></a></li>
                            <li><a class="mat" href="#"><i class="fa-solid fa-xmark"></i></a></li>
                            <li class="button__heigth">
                                <div class="but__wrapprer">
                                    <button><a class="special" href="#">GET IT NOW</a></button>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="card selected">
                    <div class="header">
                        <img src="../assets/img/h5-custom-icon-8.png" alt="">
                        <h3>Professional</h3>
                        <p class="price">$59</p>
                    </div>
                    <ul>
                        <li>4</li>
                        <li><a class="mat" href="#">30 Days</a></li>
                        <li><a class="mat" href="#"><i class="fa-regular fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-xmark"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-xmark"></i></a></li>
                        <li class="button__heigth">
                            <div class="but">
                                <button class="active"><a href="#">GET IT NOW</a></button>
                            </div>
                        </li>
                    </ul>
                </div>
                <div class="card">
                    <div class="header">
                        <img src="../assets/img/h5-custom-icon-9.png" alt="">
                        <h3>Advanced</h3>
                        <p class="price">$88</p>
                    </div>
                    <ul>
                        <li>6</li>
                        <li><a class="mat" href="#">30 Days</a></li>
                        <li><a ><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li class="button__heigth">
                            <div class="but_wrapper">
                                <button><a href="#">GET IT NOW</a></button>
                            </div>
                        </li>
                    </ul>
                </div>
            </div>
        </div>

    </div>
</template>
  
<script>
export default {


}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import'../components/Style.scss';

.row {
    width: 1350px;
    margin: 0 auto;
    padding-left: 5rem;
    padding-right: 5rem;
    background-image: url(../assets/img/page-background-img.png);
    background-size: contain;
    background-repeat: no-repeat;
    border-top: solid 2px $-border-raw;
    padding-top: 6rem;

    * {
        font-family: "Open-Sans", sans-serif;
    }

    .container {
        min-height: 500px;
        margin: 0 auto;
        width: 100%;
        margin-bottom: 12rem;
    }

    ul,
    li a {
        text-decoration: none;
        list-style: none;
        text-align: center;
        margin: 0;
        padding: 0;


    }
    a {
        text-decoration: none;
        font-size: 20px;
        width: 100%;
        color:$-text-grey ;
       
    }
    .price{
        color: #000;
        font-weight: bold;
    }
    h2{
        font-size: 70px;
        text-align: center;
        margin-bottom:30px;
    }
    .sub__title{
        text-align: center;
        font-size: 25px;
        margin-top: 0;
        padding-top: 0;
        margin-bottom: 8rem;
    }

    p {
        font-size: 20px;
        color:$-text-grey ;
    }

    li {
        border-bottom: solid 1px $-border-raw;
        height: 60px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

    }

    .li__board {
        border-top: solid 1px $-border-raw ;
        border-bottom: solid 1px $-border-raw ;
        height: 60px;
    }

    .button__heigth{
        padding-top: 30px;
        padding-bottom: 30px;
    }

    .image {
        text-align: center;
    }

    .card__wrapper {
        display: flex;
    }

    li:hover {
        background-color: $-card-bg;
    }

    li:hover .mat>a{
        color:$-card-bg;
        width: 100%;
        color: $-footer-text;
    }

    .header:hover {
        background-color: $-card-bg;
        border-top: solid 4px $-register-button;
    }

    .card {
        width: 25%;
        margin: 0;
        padding: 0;
        border-left: solid 1px $-border-raw;
        border-right: solid 1px $-border-raw;
        text-align: center;
        display: inline;
        margin: 0 auto;
    }
}

.header {
    padding-top: 30px;
    text-align: center;
    width: 100%;
    border-bottom: solid 1px $-border-raw;
    border-top: solid 4px $-border-raw-blu;
}

h3 {
    font-size: 35px;
}

ul {
    display: flex;
    flex-direction: column;
    padding-right: 30px;

}


button {
    height: 60px;
    width: 250px;
    margin-top: 20px;
    margin-bottom: 20px;
    border-color:$-border-raw ; 
    background-color:$-border-raw ;
}

.but__wrapprer {
    margin-top: 20px;
    margin-bottom: 20px;
    color:$-footer-text ;
    

}

.but__wrapprer>a {
    color:white;
    font-weight: bold;
}
button:hover {
    background-color:$-register-button ;
    border: none;
   a{
    color: white;
   }
}

</style>
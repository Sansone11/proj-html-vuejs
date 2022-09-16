<template>
    <div class="row">
        <div class="container">
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
                        <p>$12</p>
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
                            <li>
                                <div class="but__wrapprer">
                                    <button><a href="#">GET IT NOW</a></button>
                                </div>
                            </li>
                        </ul>
                    </div>
                </div>
                <div class="card selected">
                    <div class="header">
                        <img src="../assets/img/h5-custom-icon-8.png" alt="">
                        <h3>Professional</h3>
                        <p>$59</p>
                    </div>
                    <ul>
                        <li>4</li>
                        <li><a class="mat" href="#">30 Days</a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-check"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-xmark"></i></a></li>
                        <li><a class="mat" href="#"><i class="fa-solid fa-xmark"></i></a></li>
                        <li>
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
                        <p>$88</p>
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
                        <li>
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
    background-size: cover;

    * {
        font-family: "Open-Sans", sans-serif;
    }

    .container {
        min-height: 500px;
        margin: 0 auto;
        width: 100%;
    }

    ul,
    li a {
        text-decoration: none;
        list-style: none;
        text-align: center;


    }
    a {
        text-decoration: none;
        font-size: 20px;
        width: 100%;
       
    }
    

    p {
        font-size: 20px;
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
    border: none;
}

.but__wrapprer {
    margin-top: 20px;
    margin-bottom: 20px
}


.but__wrapprer>a {
    color: $-footer-text;
    font-weight: bold;
}

.card.selected {
    border-top: solid 4px $-register-button;

}

.card.selected>.card__header {
    background-color: $-card-bg;
}
</style>
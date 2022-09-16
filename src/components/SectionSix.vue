<template>
    <div class="row">
        <div class="container">
            <h2>Popular OnLine Courses</h2>
            <p class="subTitle">Lorem ipsum gravida nibh vel velit auctor aliquentean sollicitudin,lorem quis bibendum
                auci elit
                consequat ipsutis sem nibh id elit</p>
            <div class="card__wrapper">
                <div class="card">
                    <img src="../assets/img/course-5-f-img.jpg" alt="">
                    <div class="card__body">
                        <div class="text__header">
                            <div class="Tutor__wrapper">
                                <h4>Android Developer</h4>
                                <h5>David Sanders</h5>
                            </div>
                            <div class="price__free">
                                <span>FREE</span>
                            </div>
                        </div>
                        <p>Lorem ipsum dolor sit amet, te eros consultato pro quem labores petentium no sea,atqui
                            posidonum
                            interpretaris</p>
                        <ul>
                            <li><a href="#"><i class="fa-solid fa-user"></i></a>1</li>
                            <li><a href="#"><i class="fa-solid fa-tag"></i>PROGRAMMING</a></li>
                        </ul>
                    </div>
                </div>
                <div class="card">
                    <img src="../assets/img/course-6-f-img.jpg" alt="">
                    <div class="card__body">
                        <div class="text__header">
                            <div class="Tutor__wrapper">
                                <h4>Web Designing</h4>
                                <h5>Jennifer Powell</h5>
                            </div>
                            <div class="price__free">
                                <span>FREE</span>
                            </div>
                        </div>
                        <p>Lorem ipsum dolor sit amet, te eros consultato pro quem labores petentium no sea,atqui
                            posidonum
                            interpretaris</p>
                        <ul>
                            <li><a href="#"><i class="fa-solid fa-user"></i></a>1</li>
                            <li><a href="#"><i class="fa-solid fa-tag"></i>PROGRAMMING</a></li>
                        </ul>
                    </div>
                </div>
                <div class="card">
                    <img src="../assets/img/course-12-f-img.jpg" alt="">
                    <div class="card__body">
                        <div class="text__header">
                            <div class="Tutor__wrapper">
                                <h4>Financial Modeling</h4>
                                <h5>Edward Bowmann</h5>
                            </div>
                            <div class="price__pay">
                                <span>$20</span>
                            </div>
                        </div>
                        <p>Lorem ipsum dolor sit amet, te eros consultato pro quem labores petentium no sea,atqui
                            posidonum
                            interpretaris</p>
                        <ul>
                            <li><a href="#"><i class="fa-solid fa-user"></i></a>1</li>
                            <li><a href="#"><i class="fa-solid fa-tag"></i>BUSINESS</a></li>
                        </ul>
                    </div>
                </div>
            </div>
            <div class="check">
                <ul class="circle__select">
                    <li>
                        <div class="circle"></div>
                    </li>
                    <li>
                        <div class="circle special"></div>
                    </li>
                    <li>
                        <div class="circle"></div>
                    </li>
                </ul>
            </div>
            <div class="top">
                <h2>TOP</h2>
            </div>
            <div class="top_1">
                <h2>TOP</h2>
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
    position: relative;
    min-height: 600px;
    padding: 0 30px;
    border-top: solid 2px $-border-raw;
    padding-top: 5rem;

    * {
        font-family: "Open-Sans", sans-serif;
    }

    .container {
        min-height: 500px;
        margin: 0 auto;
        padding: 0, 50px;
        margin-bottom: 10rem;
        text-align: center;

        .card__wrapper {
            display: flex;
            flex-direction: row;
            column-gap: 3rem;

        }

        h2 {
            font-size: 60px;
        }

        .subTitle {
            font-size: 30px;
            max-width: 1000px;
            margin-bottom: 8rem;
            margin-left: 11rem;
        }

        .card {
            flex-basis: calc(100%/3);
            border: solid 1px $-card-border;
        }

        h4 {
            font-size: 25px;
            margin-bottom: 0;
            padding-bottom: 0;
        }

        h5 {
            font-size: 20px;
            color: $-footer-text ;
            margin-top: 0;
            padding-top: 0;
        }

        img {
            width: 100%;
        }

        ul,
        li a {
            list-style: none;
            text-decoration: none;
        }

        ul {
            display: flex;
            gap: 1rem;
        }

        .like {
            height: 20px;
            width: 20px;
        }

        .card__body {
            padding-left: 1rem;
            padding-right: 1rem;

        }

        p {
            font-size: 20px;
            max-width: 300px;
        }

        .text__header {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .price__free {
            width: 80px;
            height: 30px;
            border-radius: 30px;
            background-color: $-price-color;
            color: white;
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .price__pay {
            width: 80px;
            height: 30px;
            border-radius: 30px;
            background-color: $-top-icon-bg;
            display: flex;
            justify-content: center;
            align-items: center;
            color: white;
        }

        .check {
            padding-top: 30px;
            padding-right: 25px;
        }

        .circle__select {
            display: flex;
            align-items: center;
            justify-content: center;
            list-style: none;
            gap: 1rem;

            .circle {
                display: flex;
                align-items: center;
                justify-content: center;
                height: 11px;
                width: 11px;
                border: solid 2px $-bg-blu;
                border-radius: 50%;
                background-color: $-bg-blu;
            }

            .special {
                background-color: $-register-button;
            }
        }

        .top {
            position: absolute;
            right: 0;
            top: 5%;
            height: 80px;
            width: 80px;
            text-align: center;
            background-color: $-top-icon-bg;
            color: white;
            font-weight: bold;
        }

        .top_1 {
            position: absolute;
            right: 0;
            bottom: 2%;
            height: 80px;
            width: 80px;
            text-align: center;
            background-color: $-top-icon-bg;
            color: white;
            font-weight: bold;
        }
    }
}
</style>
  
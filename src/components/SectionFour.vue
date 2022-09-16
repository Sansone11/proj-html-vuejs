<template>
    <div class="row">
        <div class="container">
            <figure>
                <img src="../assets/img/testimonials-standard-2.png" alt="">
            </figure>
            <div class="text">
                <p>"Mroin gravida nibh vel veliauctor aliquenean sollicitudin, lorem quis bibendum auctor nisi elit
                    consequat ipsutis sem nibh id elit. Duis sed odio sit amet nivulputate cursus a sit amet
                    mauris.Morbi
                    accumsan ipsum velit.Nam nec tellus"</p>
            </div>
            <div class="testimonial">
                <div class="student__data">
                    <h2>Joan Collins</h2>
                    <p>Student</p>
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
    width:1350px;
    margin:0 auto;
    *{
    font-family: "Open-Sans",sans-serif;
    }
}

.container {
    min-height: 700px;
    width: 100%;
    background-image: url(../assets/img/h5-parallax-img-1.png);
    background-size: cover;
    color: white;
    padding-top: 40px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;

    p {
        font-size: 20px;
        max-width: 700px;
    }

    figure {
        margin-bottom: 40px;
    }

    .text {
        margin-bottom: 50px;
    }

    .student__data {
        text-align: center;
    }
    .check{
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
            border: solid 2px;
            border-radius: 50%;
            color: white;
        }

        .special {
            background-color: white;
        }
    }

    .testimonial {
        margin-top: 0;
        padding-top: 0;
    }
}
</style>
<template>
    <div>
        <div class="row">
            <h2>The Trusted Name </h2>
            <h2>for In-Home Tutoring.</h2>
            <p>Lorem ipsum gravida nibh vel velit auctor aliquentean sollicitudin,lorem quis bibendum auci elit
                consequat ipsutis sem nibh id elited odio siy amet nibcursus a sit amet mauris.</p>
            <h5>LEARN MORE</h5>
            <div class="imgBg">
                <div class="top">
                    <span>TOP</span>
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
    padding-left: 50px;

    * {
        font-family: "Open-Sans", sans-serif;
    }

    h2 {
        font-size: 60px;
        margin: 0;
    }

    h5 {
        font-weight: bold;
        color: $-top-icon-bg;
        font-size: 25px;
    }

    p {
        font-size: 20px;
        line-height: 30px;
        color:$-text-grey ;
    }

    .imgBg {
        background-image: url(../assets/img/h5-img-1.jpg);
        background-size: cover;
        height: 700px;
        width: 100%;
        position: relative;
    }

    .top {
        height: 80px;
        width: 80px;
        text-align: center;
        background-color: $-top-icon-bg;
        color: white;
        font-weight: bold;
        font-size: 10px;
        position: absolute;
        right: 0;
        bottom: 35%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        font-size: 20px;
        font-weight: bold;
    }
}

</style>
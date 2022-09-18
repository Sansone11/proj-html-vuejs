<template>
    <div class="row">
        <div class="container">
            <div class="card">
                <img class="logo" src="../assets/img/h5-client-5-h.png" alt="">
            </div>
            <div class="card">
                <img class="logo" src="../assets/img/h5-client-1-h.png" alt="">
            </div>
            <div class="card">
                <img class="logo" src="../assets/img/h5-client-2-h.png" alt="">

            </div>
            <div class="card">
                <img class="logo" src="../assets/img/h5-client-1-h.png" alt="">
            </div>
        </div>
        <div class="top">
            <span>TOP</span>
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
    border-top: solid 2px $-border-raw;

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
            display: flex;
            flex-direction: column;
            align-content: center;
            justify-content: center;
        }

    * {
        font-family: "Open-Sans", sans-serif;
    }
    .container {
    display: flex;

    .card {
        flex-basis: calc(100%/4);
        height: 300px;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .card :hover.logo{
        background-color:white ;
        opacity: 0.5;
        color:$-footer-text;
    }
}
}



</style>
  
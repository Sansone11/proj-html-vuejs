<template>
    <div class="row">
        <div class="container">
            <div class="card">
                <img src="../assets/img/h5-client-5-h.png" alt="">
            </div>
            <div class="card">
                <img src="../assets/img/h5-client-1-h.png" alt="">
            </div>
            <div class="card">
                <img src="../assets/img/h5-client-2-h.png" alt="">

            </div>
            <div class="card">
                <img src="../assets/img/h5-client-1-h.png" alt="">
            </div>
        </div>
        <div class="top">
            <h2>TOP</h2>
        </div>
    </div>
</template>
  
<script>
export default {


}
</script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import'../assets/Style.scss';

.row {
    width: 1200px;
    margin: 0 auto;
    position: relative;
    .top{
            position: absolute;
            right: 0;
            top: 5%;
            height: 60px;
            width: 60px;
            text-align: center;
            background-color: $-top-icon-bg;
            color: white;
            font-weight: bold;
        }
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
}
</style>
  
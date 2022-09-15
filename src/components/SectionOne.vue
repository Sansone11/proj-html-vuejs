<template>
    <div class="row">
        <div class="card__wrapper">
        <div class="card">
             <img src="../assets/img/h5-custom-icon-1.png" alt=""> 
             <h3>Lenguages</h3>
        </div>
        <div class="card">
            <img src="../assets/img/h5-custom-icon-2.png" alt="">
            <h3>Software</h3>
        </div>
        <div class="card">
            <img src="../assets/img/h5-custom-icon-3.png" alt="">
            <h3>Business</h3>
        </div>
        <div class="card">
            <img src="../assets/img/h5-custom-icon-4.png" alt="">
            <h3>Chemistry</h3>
        </div>
        <div class="card">
            <img src="../assets/img/h5-custom-icon-5.png" alt="">
            <h3>Science</h3>
        </div> 
        <div class="card">
            <img src="../assets/img/h5-custom-icon-6.png" alt="">
            <h3>DYX&Craft</h3>
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
    @import'../assets/Style.scss';
    .row{
        margin: 0 auto;
        height: 400px;
        padding-top:80px;
        width: 1200px;
        margin:0 auto;
    }
    .card__wrapper{
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        padding-left: 30px;
        padding-right: 30px;
        column-gap: 2rem;
        .card{
            flex-basis: calc(100%/6);
            border: solid  1px $-card-border;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 270px;
            gap:1.50rem;
            background-color: $-card-bg;
            h3{
                font-size: 25px;
            }
        }
    }
  
  </style>
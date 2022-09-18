<template>
    <div class="row">
        <div class="container">
            <div class="world">

            </div>
            <div class="children">
                <h2>Empowering Children to Reach Their Potential</h2>
                <p>Lorem ipsum gravida nibh vel velit auctor aliquentean sollicitudin,lorem quis bibendum auci elit consequat ipsutis sem nibh id elited odio siy amet nibcursus a sit amet mauris.</p>
                <div class="stats">
                    <div class="num__wrapper" >
                        <h3 class="number">168</h3>
                        <p class="state__data">User Stories</p>

                    </div>
                    <div class="num__wrapper">
                        <h3 class="number">347</h3>
                        <p class="state__data">Events</p>
                    </div>
                    <div class="top">
                        <span>TOP</span>
                    </div>
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
    padding-top: 80px;
    padding-bottom: 40px;
    position: relative;
    margin-bottom: 3rem;

    * {
        font-family: "Open-Sans", sans-serif;
    }

    .container {
        display: flex;
        flex-direction: row;
        max-height: 500px;
        column-gap: 4rem;

        .world {
            flex-basis: 50%;
            background-image: url(../assets/img/h5-img-2.jpg);
            background-size: contain;
            background-repeat: no-repeat;
        }

        .children {
            flex-basis: 50%;
            max-height: 600px;
            max-width: 400px;
            display: flex;
            flex-direction: column;

            h2 {
                font-size: 50px;
                max-width: 400px;
                margin-bottom: 0;
            }

            p {
                font-size: 20px;
                max-width: 400px;
                margin-bottom: 0;
                color:$-text-grey ;
            }

            .stats {
                display: inline-block;
                padding-top: 0;
                margin-top: 0;

                .num__wrapper {
                    width: 50%;
                    display: inline-block;
                    padding-top: 0;
                    margin-top: 0;

                    .state__data {
                        margin-top: 0;
                        padding-top: 0;
                        text-align: left;
                        font-size: 20px;
                        font-weight: bold;
                        color: $-top-icon-bg ;
                    }
                }

                .number {
                    font-size: 50px;
                    color: $-top-icon-bg ;
                    margin-right: 5rem;
                    text-align: left;
                    margin-bottom: 0;
                    padding-bottom: 0;

                }
            }
        }
    }

    .top {
        position: absolute;
        right: 0;
        bottom: 1%;
        height: 80px;
        width: 80px;
        text-align: center;
        background-color: $-top-icon-bg;
        color: white;
        font-weight: bold;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        font-size: 20px;
        font-weight: bold;
    }
}
    
  </style>
  
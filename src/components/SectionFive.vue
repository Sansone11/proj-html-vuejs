<template>
    <div class="row">
        <div class="container">
            <div class="side__card">
                <ul class="service">
                    <li class="active select"><a href="#">What We Do</a></li>
                    <li class="select"><a class="mat" href="#">Degree Programme</a></li>
                    <li class="select"><a class="mat" href="#">Carrer Achivevements</a></li>
                    <li class="select"><a class="mat" href="#">Personal Management</a></li>
                    <li class="select"><a class="mat" href="#">Steps To Success</a></li>
                    <li class="select"><a  class="mat" href="#">Knowledge Transfer</a></li>
                </ul>
            </div>
            <div class="Learning__service">
                <h2>Learn Possibilities</h2>
                <p>Lorem ipsum gravida nibh vel veliauctor aliquenean sollicitudin, lorem quis bibendum auctor nisi elit
                    consequat ipsutis sem nibh id elit. Duis sed odio sit amet nivulputate cursus a sit amet
                    mauris.Morbi accumsan ipsum velit.Nam nec tellus</p>
                <ul class="solutions">
                    <li>We enric lives through learning.</li>
                    <li>Maximizing potential through individual attention.</li>
                    <li>The trusted name for specialized training.</li>
                    <li>people teach.People learn.This is where they connect</li>
                </ul>
                <figure><img src="../assets/img/h12-tabs-icon-1.png" alt=""></figure>
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
    padding-top: 8rem;
    position: relative;

    .container {
        display: flex;
        flex-direction: row;
        column-gap: 4rem;
        margin-bottom: 80px;

        *{
            font-family: "Open-Sans", sans-serif;
        }

        .side__card {
            flex-basis: 30%;

            li {
                display: flex;
                justify-content: flex-start;
                align-items: center;
                border: solid 1px $-card-border;
                height: 80px;
                padding-left: 20px;
            }

            a {
                text-decoration: none;
                font-size: 20px;
                color: $-footer-text ;
            }

            .active {
                border-left: solid 8px $-top-icon-bg;
            }

            .active>a {
                color: $-top-icon-bg;
            }
        }

        .Learning__service {
            flex-basis: 70%;

        }

        h2 {
            font-size: 50px;
        }

        p {
            font-size: 20px;
            max-width: 600px;
            margin-bottom: 40px;
            color:$-text-grey ;
        }

        .solutions {
            line-height: 50px;
            font-size: 20px;
            max-width: 410px;
            color:$-text-grey ;
        }
        .select:hover {
            border-left: solid 8px $-top-icon-bg;
            color: $-top-icon-bg;
            .mat{
             color: $-top-icon-bg;
         }
        }
         
        .solutions>li:hover {
            color: $-top-icon-bg;
        }
        img {
            height: 180px;
            width: 180px;
            position: absolute;
            right: 6%;
            bottom: 6%;
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
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            font-size: 20px;
            font-weight: bold;
        }
    }

    ul,
    li {
        list-style: none;
    }
}
</style>
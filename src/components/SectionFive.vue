<template>
    <div class="row">
        <div class="container">
            <div class="side__card">
                <ul class="service">
                    <li class="active"><a href="#">What We Do</a></li>
                    <li><a href="#">Degree Programme</a></li>
                    <li><a href="#">Carrer Achivevements</a></li>
                    <li><a href="#">Personal Management</a></li>
                    <li><a href="#">Steps To Success</a></li>
                    <li><a href="#">Knowledge Transfer</a></li>
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
                    <h2>TOP</h2>
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
@import'../assets/Style.scss';

.row {
    width: 1200px;
    margin: 0 auto;
    padding-top: 8rem;
    position: relative;

    .container {
        display: flex;
        flex-direction: row;
        column-gap: 4rem;
        margin-bottom: 80px;

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
        }

        .solutions {
            line-height: 50px;
            font-size: 20px;
            max-width: 410px;
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
        }
    }

    ul,
    li {
        list-style: none;
    }
}
</style>
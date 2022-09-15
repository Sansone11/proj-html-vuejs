<template>
    <div class="row">
        <div class="container">
            <div class="card__wrapper">
                <div class="card">
                    <div class="card__header">
                        <h3>Save up to 40% by payng weekly</h3>
                    </div>
                    <div>
                        <ul>
                            <li><a href="#">Number of Courses</a></li>
                            <li><a href="#">Time</a></li>
                            <li><a href="#">Web Designing</a></li>
                            <li><a href="#">Human-Centered Design</a></li>
                            <li><a href="#">Basic Markrting</a></li>
                            <li><a href="#">Python for Everybody</a></li>
                            <li><a href="#">Android Developer</a></li>
                            <li><a href="#">Business English</a></li>
                        </ul>
                    </div>
                </div>
                <div class="card">
                    <div class="image">
                        <img src="../assets/img/h5-custom-icon-7.png" alt="">
                    </div>
                    <div class="card__header">
                        <h3>Standard</h3>
                        <p>$12</p>
                    </div>
                    <div>
                        <ul>
                            <li>4</li>
                            <li><a href="#">15 Days</a></li>
                            <li><a href="#">#</a></li>
                            <li><a href="#">#</a></li>
                            <li><a href="#">#</a></li>
                            <li><a href="#">#</a></li>
                            <li><a href="#">#</a></li>
                            <li><a href="#">#</a></li>
                            <li>
                            <div class="but__wrapprer">
                                <button><a href="#">GET IT NOW</a></button>
                            </div>
                        </li>
                        </ul>
                    </div>
                </div>
                <div class="card">
                    <div class="image">
                        <img src="../assets/img/h5-custom-icon-8.png" alt="">
                    </div>
                    <div class="card__header">
                        <h3>Professional</h3>
                        <p>$59</p>
                    </div>
                    <ul>
                        <li>4</li>
                        <li><a href="#">30 Days</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li>
                            <div class="but">
                                <button class="active"><a href="#">GET IT NOW</a></button>
                            </div>
                        </li>
                    </ul>
                </div>
                <div class="card">
                    <div class="image">
                        <img src="../assets/img/h5-custom-icon-9.png" alt="">
                    </div>
                    <div class="card__header">
                        <h3>Advanced</h3>
                        <p>$88</p>
                    </div>
                    <ul>
                        <li>6</li>
                        <li><a href="#">30 Days</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li><a href="#">#</a></li>
                        <li>
                            <div class="but_wrapper">
                                <button ><a href="#">GET IT NOW</a></button>
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
@import'../assets/Style.scss';

.row {
    width: 1200px;
    margin: 0 auto;
    padding-left: 5rem;
    padding-right: 5rem;

    .container {
        min-height: 500px;
        margin: 0 auto;
        width: 100%;
    }

    ul,
    li a {
        text-decoration: none;
        list-style: none;
    }

    a {
        text-decoration: none;
        font-size: 20px;
    }
    p{
        font-size: 20px;
    }

    li {
        border: solid 1px $-border-raw;
        height: 60px;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .image{
        text-align: center;
    }

    .card__wrapper {
        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
    }

    .card {
    border-top:solid 4px $-bg-blu;
    flex-basis: calc(100%/4);
    padding-top: 40px;
    border-left: solid 1px $-border-raw;
    }
}

.card__header {
    text-align: center;
    width: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

h3 {
    font-size: 35px;
}

ul {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    width: 100%;
    padding-right: 30px;

}
button{
    height: 60px;
    width: 250px;
    margin-top: 20px;
    margin-bottom: 20px;
    border: none;
}
.but__wrapprer{
    margin-top: 20px;
    margin-bottom: 20px
}

.active>a{
    color: white;
    font-weight: bold;
    background-color:$-register-button ;
    font-weight: bold;
}
.active{
    color: white;
    font-weight: bold;
    background-color:$-register-button ;
    font-weight: bold;
}
.but__wrapprer>a{
    color: $-footer-text;
    font-weight: bold;
}
</style>
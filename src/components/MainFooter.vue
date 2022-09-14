<template>
    <div class="main__footer">
      <div class="content__wrapper">
        <div class="logo list">
          <img src="../assets/img/footer-logo-1.png" alt="">
          <ul>
            <li v-for="experience in logoList" :key="experience" ><a href="#">{{experience}}</a></li>
          </ul>
          <span><a href="#">1-677-124-44227</a></span>
          <span><a href="#">Man-Sat 8.00 - 18.00</a></span>
        </div>
        <div class="course list">
          <h2 class="sub__title">Popular Courses</h2>
          <ul>
            <li v-for="business in courseBusiness" :key="business" class="study"><a href="#">{{business}}</a></li>
          </ul>
          <ul>
            <li v-for="computed in courseComputing" :key="computed" class="study"><a href="#">{{computed}}</a></li>
          </ul>
          <ul>
            <li v-for="spanish in courseSpanish" :key="spanish" class="study"><a href="#">{{spanish}}</a></li>
          </ul>
        </div>
        <div class="support list">
          <h2 class="sub__title">Support</h2>
          <ul>
            <li v-for="help in support" :key="help"><a href="#">{{help}}</a></li>
          </ul>
        </div>
        <div class="world__map">
          <h2 id="world__title">Flexible Learning</h2>
          <img src="../assets/img/footer-img-1.png" alt="">
        </div>
      </div>
      <div class="copyrights">
        <div class="company">
          <a href="#">Copyrigths 2017 @Mikado Themes</a>
        </div>
        <div class="follow__us">
          <ul class="icons">
            <li><a href="#">CALL +44 300 303 0266</a></li>
            <li><a href="#">FOLLOW US</a></li>
          </ul>
          <ul class="icons">
            <li><a href="#">#</a></li>
            <li><a href="#">#</a></li>
            <li><a href="#">#</a></li>
          </ul>
        </div>
      </div>
    </div>
  </template>
  
  <script>
  export default {
   data(){
    return{
      logoList:['Providing Life Changing','Experience Trough','Education.Class that Fit Your','Busy Life.Closer to Home'],
      courseBusiness:['Business English','Preston Marshal'],
      courseComputing:['Social Computing','David Sanders'],
      courseSpanish:['Learn Spanish','Jennie King'],
      support:['User dashboard','Contact Us','FAQ','Course Offer','Events']
    }
    
      
   }
  }
  </script>
  
  <!-- Add "scoped" attribute to limit CSS to this component only -->
  <style scoped lang="scss">
   @import'../assets/Style.scss';
   .main__footer{
    background-color:$-footer-bg;
    padding: 0 40px;
    padding-top: 40px;
    .content__wrapper{
      display: flex;
      flex-direction: row;
      border-bottom: solid 2px $-footer-text ;
      justify-content: center;
      align-items: baseline;
      height: 300px;
      width: 100%;
      .world__map>img{
        width: 230px;
        height: 120px;
      }
      .logo>img{
        height: 30px;
        width: 170px;
        color: $-footer-title;
        margin-left: 35px;
      }
    }
    ul{
      list-style: none;
      margin-right: auto;
    }
    // .list>li{
    //   line-height: 25px;
    // }
    
    a{
      text-decoration: none;
      color:$-footer-text;
      font-size: 16px;
      line-height: 20px;
    }
    .copyrights{
      display: flex;
      justify-content: space-between;
      align-items: center;
      .follow__us{
        display: flex;
        align-items: center;
        height: 100px;
        .icons{
          display: flex;
          align-items: center;
          height: 100px;
          gap: 2rem;
        }
      }
    }
    h2{
      color:$-footer-title; 
    }
    .sub__title{
      margin-left: 35px;
    }
    #world__title{
      text-align: left;
    }
    .study{
      font-weight: bold;
    }
    .list{
      flex-basis: calc(100%/4);
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      align-items: flex-start;
      
    }
    
    span{
      margin-left: 40px;
    }
   }
  </style>
  
<template>
  <div class="main">
      <div class="section-1">
          <div class="section-1-left">
              <div>EVERY MOMENT COUNTS</div>
              <div class="line-1"></div>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <button>OUR MISSION</button>
          </div>
          <div class="section-1-right">
              <div class="container-1">
                  <div class="num-text">
                    <div class="num"><i class="far fa-heart"></i>20<span>3</span>2</div>
                    <div class="text1">Volunters worldwide</div>
                  </div>
                  <div class="num-text">
                    <div class="num"><i class="fas fa-globe"></i>1<span>3</span>2</div>
                    <div class="text1">Active projects</div>
                  </div>
                  <div class="num-text">
                    <div class="num"><i class="fas fa-dollar-sign"></i><span>3</span>.8M</div>
                    <div class="text1">Donated</div>
                  </div>

              </div>
          </div>
      </div>
      <Section2 />
      <Section3 />
      <div class="section-4">VIEW ALL OUR CAUSES</div>
      <Section5 />
      <Section6 />
  </div>
</template>

<script>

import Section2 from './Section2.vue'
import Section3 from './Section3.vue'
import Section5 from './Section5.vue'
import Section6 from './Section6.vue'

export default {
   nome: 'Main',
   components:{
       Section2,
       Section3,
       Section5,
       Section6
   }
}
</script>

<style lang="scss" scoped>

@import '../assets/vars.scss';
@import '../assets/mixin.scss';

.main{
    min-height: 400px;
    .section-1{
        display: flex;
        height: 350px;

        .section-1-left{
            height: 100%;
            width: 70%;
            background-color: white;
            padding: 45px;
            .line-1{
                height: 3px;
                width: 100px;
                background-color: $color-orange;
                margin: 20px 0;
            }
            p{
                color: $color-gray;
                margin: 20px 0;
            }
            button{
                color: white;
                background-color: $color-orange;
                padding: 6px 10px;
                border: $color-orange;
                cursor: pointer;
            }
            
        }
        .section-1-right{
            @include flex(ja);
            flex-direction: column;
            height: 100%;
            width: 30%;
            text-align: center;
            color: white;
            background-image: url('../assets/images/home-content-bg-1.jpg');

            .num-text{
                margin: 25px;
                font-size: 18px;
                .num{
                    font-size: 24px;
                    span{
                        font-size: 28px;
                    }
                    .far, .fas{
                        margin-right: 6px;
                    }
                }
                .text1{
                    font-size: 14px;
                }
            }
        }
        
    }
    
    .section-4{
        height: 70px;
        color: white;
        font-size: 11px;
        background-color: #ed6864;
        text-align: center;
        line-height: 70px;
    }
}

</style>
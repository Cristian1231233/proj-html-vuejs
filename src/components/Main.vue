<template>
  <div class="main">
      <div class="section-1">
          <div class="section-1-left">
              <div>EVERY MOMENT COUNTS</div>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <button>OUR MISSION</button>
          </div>
          <div class="section-1-right">
              <div class="container-1">
                  <div class="num-text">
                    <div>2032</div>
                    <div>Volunters worldwide</div>
                  </div>
                  <div class="num-text">
                    <div>132</div>
                    <div>Active projects</div>
                  </div>
                  <div class="num-text">
                    <div>3.8M</div>
                    <div>Donated</div>
                  </div>

              </div>
          </div>
      </div>
      <div class="section-2">
          <div>OUR VALUE</div>
          <div class="line"></div>
          <div>Think Big.Act Bigger.</div>
          <div class="container-ciclo-2">
              <div class="element">
                  <div class="symbol"></div>
                  <div class="title">Clean Water</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste? Error vero alias tenetur iure sunt non libero omnis blanditiis. Non quam in repudiandae quia?</p>
                  <button>Learn More</button>
              </div>
              <div class="element">
                  <div class="symbol"></div>
                  <div class="title">Clean Water</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste? Error vero alias tenetur iure sunt non libero omnis blanditiis. Non quam in repudiandae quia?</p>
                  <button>Learn More</button>
              </div>
              <div class="element">
                  <div class="symbol"></div>
                  <div class="title">Clean Water</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste? Error vero alias tenetur iure sunt non libero omnis blanditiis. Non quam in repudiandae quia?</p>
                  <button>Learn More</button>
              </div>
              <div class="element">
                  <div class="symbol"></div>
                  <div class="title">Clean Water</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste? Error vero alias tenetur iure sunt non libero omnis blanditiis. Non quam in repudiandae quia?</p>
                  <button>Learn More</button>
              </div>
          </div>
      </div>
      <div class="section-3">VIEW ALL OUR CAUSES</div>
  </div>
</template>

<script>
export default {
   nome: 'Main',
   
}
</script>

<style lang="scss" scoped>

.main{
    min-height: 400px;
    .section-1{
        display: flex;
        height: 350px;
        background-color: red;
        .section-1-left{
            height: 100%;
            width: 70%;
            background-color: white;
            padding: 45px;
            p{
                margin: 10px;
            }
            button{
                margin: 10px 10px;
            }
            
        }
        .section-1-right{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100%;
            width: 30%;
            text-align: center;
            color: white;
            background-color: rgb(243, 52, 52);

            .num-text{
                margin: 20px;
                font-size: 18px;
            }
        }
        
    }
    .section-2{
            height: 300px;
            text-align: center;
            margin: 60px;

            // .line{
            //     // height: 3px;
            //     // width: 60px;
            //     // background-color: yellow;
                
            // }
            .container-ciclo-2{
                display: flex;
                margin-top: 120px;
                .element{
                    margin-right: 13px;
                }
            }
    }
    .section-3{
        height: 70px;
        color: white;
        font-size: 11px;
        background-color: #ed6864;
        text-align: center;
        line-height: 70px;
    }
}

</style>
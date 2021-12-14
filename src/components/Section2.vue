<template>
  <div class="section-2">
          <div>OUR VALUE</div>
          <div class="line"></div>
          <div>Think Big.Act Bigger.</div>
          <div class="container-ciclo-2">
              <div class="element">
                  <div class="symbol"><i class="fas fa-tint"></i></div>
                  <div class="title">Clean Water</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste? </p>
                  <button>Learn More</button>
              </div>
              <div class="element">
                  <div class="symbol"><i class="fas fa-stethoscope"></i></div>
                  <div class="title">Clean Water</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste? </p>
                  <button>Learn More</button>
              </div>
              <div class="element">
                  <div class="symbol"><i class="fas fa-graduation-cap"></i></div>
                  <div class="title">Clean Water</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste? </p>
                  <button>Learn More</button>
              </div>
              <div class="element">
                  <div class="symbol"><i class="fab fa-pagelines"></i></div>
                  <div class="title">Clean Water</div>
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste? </p>
                  <button>Learn More</button>
              </div>
          </div>
      </div>
</template>

<script>
export default {
    nome: 'Section2'
}
</script>

<style lang="scss" scoped>

@import '../assets/vars.scss';

.section-2{
            min-height: 500px;
            text-align: center;
            background-image: url('../assets/images/home-content-bg-2.jpg');
            background-position: center;
            background-size: 900px;
            background-position-y: 40px;
            padding: 60px;

            // .line{
            //     // height: 3px;
            //     // width: 60px;
            //     // background-color: yellow;
                
            // }
            .container-ciclo-2{
                display: flex;
                margin-top: 120px;
                .element{
                    width: 400px;
                    margin-right: 13px;
                    .symbol, .title, p, button{
                        margin-bottom: 15px;
                    }
                    .symbol{
                        font-size: 33px;
                        color: $color-orange;
                    }
                    .title{
                        color: white;
                        font-size: 18px;
                    }
                    p{
                        color: $color-gray;
                    }
                    button{
                        color: white;
                        background-color: $color-orange;
                        border-color: $color-orange;
                        padding: 4px 10px;
                        cursor: pointer;
                    }
                }
            }
    }

</style>
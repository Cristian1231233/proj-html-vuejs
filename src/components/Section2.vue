<template>
  <div class="section-2">
          <div class="title-2">OUR VALUE</div>
          <div class="line-2"></div>
          <div class="testo-2">Think Big.Act Bigger.</div>
          <div class="container-ciclo-2">
              <div class="element" v-for="(element, index) in elemetList"
              :key="index"
              >
                  <div class="symbol"><i :class="element.symbol"></i></div>
                  <div class="title">{{element.title}}</div>
                  <p>{{element.paragrafo}}</p>
                  <button>{{element.bottone}}</button>
              </div>
          </div>
      </div>
</template>

<script>
export default {
    nome: 'Section2',
    props:{
        elemetList: Array
    }
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
            .title-2{
                color: white;
                font-size: 23px;
                margin: 20px;
            }
            .testo-2{
                color: $color-gray;
            }

            .line-2{
                height: 2px;
                width: 100px;
                background-color: $color-orange;
                margin: 20px auto;

            }
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
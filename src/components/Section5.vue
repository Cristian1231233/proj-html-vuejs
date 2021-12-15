<template>
  <div class="section-5">
     <div class="contenitore-top">
         <div class="titolo">LATEST ARTICLES</div>
         <div class="line-5"></div>
         <div class="text-5">Togheter we make all the difference</div>
     </div>
     <div class="container-5">
         <div class="image-text">
             <div class="image">
                 <img src="../assets/images/photo-1444213007800-cff19e1677ac-200x150.jpg" alt="">
             </div>
             <div class="text">
                <div class="orange">Understanding community complexities</div>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
             </div>
         </div>
        <div class="container-images">
         <div class="images-texts" v-for="(item, index) in imagesTexts"
         :key="index"
         >
             <div class="images">
                 <img :src="require(`../assets/images/${item.image}`)" alt="">
             </div>
             <div class="texts">
                 <div class="orange">{{item.testo}}</div>
                 <p>{{item.paragrafo}}</p>
                 <p>{{item.paragrafo2}}</p>
             </div>
         </div>
         
        </div>
     </div>
     <div class="altro-text">
         VIEW ALL OUR ARTICLES
     </div>
  </div>
</template>

<script>
export default {
    nome: 'Section5',
    props:{
        imagesTexts: Array
    }
}
</script>

<style lang="scss" scoped>

@import '../assets/vars.scss';
@import '../assets/mixin.scss';

.section-5{
    min-height: 400px;
    background-color: linear-gradient($color-gray, white);
    .contenitore-top{
        text-align: center;
        margin: 60px 0;
        
        .titolo{
            font-size: 23px;
            margin-bottom: 20px;
        }
        .line-5{
            height: 2px;
            width: 100px;
            background-color: $color-orange;
            margin: 20px auto;
        }
        .text-5{
            color: $color-gray;
            margin-top: 20px;
        }
    }
    .container-5{
        @include flex(j);
        width: 700px;
        min-height: 300px;
        margin: 0 auto;
        p{
            color: $color-gray;
        }
        .image-text{
            width: 50%;
            min-height: 300px;
            .image{
                width: 100%;
                img{
                    width: 100%;
                }
            }
            .text{
                padding: 15px;
                .orange{
                    color: $color-orange;
                    margin: 10px 0;
                }
            }
        }
        .container-images{
            height: 100%;
            width: 45%;
        }
        .images-texts{
            display: flex;
            width: 100%;
            margin-bottom: 30px;
            margin-left: auto;
            .images{
                width: 86px;
                img{
                    width: 100%;
                    height: 100%;
                }
            }
            .texts{
                font-size: 12px;
                margin: 3px 10px;
                p{
                    margin-top: 4px;
                }
                .orange{
                    color: $color-orange;
                }
            }
        }
        .images-texts:last-child{
            margin-bottom: none;
        }
    }
    .altro-text{
        width: 700px;
        height: 40px;
        color: white;
        font-size: 13px;
        text-align: center;
        line-height: 40px;
        background-color: #ed6864;
        margin: 50px auto;
    }
}

</style>
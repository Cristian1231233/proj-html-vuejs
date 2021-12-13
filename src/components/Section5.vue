<template>
  <div class="section-5">
     <div class="titolo">
         <div>LATEST ARTICLES</div>
         <div>line</div>
         <div>Togheter we make all the difference</div>
     </div>
     <div class="container-5">
         <div class="image-text">
             <div class="image">
                 <img src="../assets/images/photo-1444213007800-cff19e1677ac-200x150.jpg" alt="">
             </div>
             <div class="text">
                <div class="yellow">Understanding community complexities</div>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
             </div>
         </div>
        <div class="container-images">
         <div class="images-texts">
             <div class="images">
                 <img src="../assets/images/photo-1444664597500-035db93e2323-177x142.jpg" alt="">
             </div>
             <div class="texts">
                 <div class="yellow">Understanding community complexities</div>
                 <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
             </div>
         </div>
         <div class="images-texts">
             <div class="images">
                 <img src="../assets/images/photo-1444664597500-035db93e2323-177x142.jpg" alt="">
             </div>
             <div class="texts">
                 <div class="yellow">Understanding community complexities</div>
                 <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
             </div>
         </div>
         <div class="images-texts">
             <div class="images">
                 <img src="../assets/images/photo-1444664597500-035db93e2323-177x142.jpg" alt="">
             </div>
             <div class="texts">
                 <div class="yellow">Understanding community complexities</div>
                 <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
             </div>
         </div>
         <div class="images-texts">
             <div class="images">
                 <img src="../assets/images/photo-1444664597500-035db93e2323-177x142.jpg" alt="">
             </div>
             <div class="texts">
                 <div class="yellow">Understanding community complexities</div>
                 <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
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
    nome: 'Section5'
}
</script>

<style lang="scss" scoped>

.section-5{
    min-height: 500px;
    .titolo{
        text-align: center;
        margin: 60px 0;
    }
    .container-5{
        display: flex;
        justify-content: space-between;
        width: 700px;
        min-height: 300px;
        margin: 0 auto;
        border: 1px solid black;
        .image-text{
            width: 45%;
            min-height: 300px;
            border: 1px solid black;
            .image{
                width: 100%;
                img{
                    width: 100%;
                }
            }
            .text{
                padding: 14px;
                .yellow{
                    color: #FEC866;
                    margin: 10px 0;
                }
            }
        }
        .container-images{
            height: 100%;
            width: 45%;
            border: 1px solid black;
        }
        .images-texts{
            display: flex;
            width: 100%;
            border: 1px solid black;
            margin-bottom: 30px;
            .images{
                width: 76px;
                img{
                    width: 100%;
                    height: 100%;
                }
            }
            .texts{
                font-size: 12px;
                margin: 7px 10px;
                .yellow{
                    color: #FEC866;
                }
            }
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
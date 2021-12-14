<template>
  <div class="section-3">
     <div class="titolo-3">RECENT CAUSES</div>
     <div class="line-3">line</div>
     <div class="p-3">We run projects in over 30 countries in 5 contintents</div>
     <div class="container-ciclo-3">
         
         <div class="photo">
             <img src="../assets/images/avada-charity-fair-trade-featured-200x150.jpg" alt="">
         </div>
         <div class="photo">
             <img src="../assets/images/avada-charity-fair-trade-featured-200x150.jpg" alt="">
         </div>
         <div class="photo">
             <img src="../assets/images/avada-charity-fair-trade-featured-200x150.jpg" alt="">
         </div>
         <div class="photo">
             <img src="../assets/images/avada-charity-fair-trade-featured-200x150.jpg" alt="">
         </div>
        
     </div>
 </div>
</template>

<script>
export default {
    nome: 'Section3'
}
</script>

<style lang="scss" scoped>

@import '../assets/vars.scss';


.section-3{
    .titolo-3, .line-3{
        margin: 15px;
    }
    text-align: center;
    padding: 30px;
    .container-ciclo-3{
        margin: 60px auto;
        display: flex;
       
        .photo{
            width: 200px;
            margin-right: 20px;
            margin-left: 70px;
            img{
                width: 100%;
            }
        }
    }
}

</style>
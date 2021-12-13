<template>
  <div class="section-3">
     <div>RECENT CAUSES</div>
     <div>line</div>
     <div>We run projects in over 30 countries in 5 contintents</div>
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

.section-3{
    text-align: center;
    padding: 30px;
    .container-ciclo-3{
        margin: 20px auto;
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
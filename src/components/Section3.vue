<template>
  <div class="section-3">
     <div class="titolo-3">RECENT CAUSES</div>
     <div class="line-3"></div>
     <div class="p-3">We run projects in over 30 countries in 5 contintents</div>
     <div class="container-ciclo-3">
         
         <div class="photo" v-for="(photo, index) in photoList"
         :key="index"
         >
             <img :src="require(`../assets/images/${photo}`)" alt="">
         </div>
     </div>
 </div>
</template>

<script>
export default {
    nome: 'Section3',
    props:{
        photoList: Array
    }
}
</script>

<style lang="scss" scoped>

@import '../assets/vars.scss';
@import '../assets/mixin.scss';


.section-3{
    .titolo-3, .line-3{
        margin: 15px;
    }
    .titolo-3{
        font-size: 23px;
    }
    .line-3{
        height: 2px;
        width: 100px;
        background-color: $color-orange;
        margin: 20px auto;
    }
    .p-3{
        color: $color-gray;
    }
    text-align: center;
    padding: 30px;
    .container-ciclo-3{
        width: 900px;
        margin: 50px auto;
        @include flex(jsa);
        .photo{
            width: 200px;
            img{
                width: 100%;
            }
        }
    }
}

</style>
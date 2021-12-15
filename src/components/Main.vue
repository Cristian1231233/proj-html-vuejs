<template>
  <div class="main">
      <Section1 />
      <Section2 :elemetList="elemetList" />
      <Section3 :photoList="photoList" />
      <div class="section-4">VIEW ALL OUR CAUSES</div>
      <Section5 :imagesTexts="imagesTexts" />
      <Section6 />
  </div>
</template>

<script>

import Section1 from './Section1.vue'
import Section2 from './Section2.vue'
import Section3 from './Section3.vue'
import Section5 from './Section5.vue'
import Section6 from './Section6.vue'

export default {
   nome: 'Main',
  
   data(){
       return{
           photoList: [
               'avada-charity-fair-trade-featured.jpg',
               'avada-charity-shelter-featured.jpg',
               'avada-charity-farming-featured-200x150.jpg',
               'avada-charity-vaccines-featured.jpg'
           ],
           elemetList: [
               {
                   symbol: 'fas fa-tint',
                   title: 'Clean Water',
                   paragrafo: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste?',
                   bottone: 'Learn More'
               },
               {
                   symbol: 'fas fa-stethoscope',
                   title: 'Vaccinations',
                   paragrafo: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste?',
                   bottone: 'Learn More'
               },
               {
                   symbol: 'fas fa-graduation-cap',
                   title: 'Education',
                   paragrafo: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste?',
                   bottone: 'Learn More'
               },
               {
                   symbol: 'fab fa-pagelines',
                   title: 'Farming',
                   paragrafo: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Corporis porro, vitae explicabo odio voluptatum iste?',
                   bottone: 'Learn More'
               },

           ],
           imagesTexts: [
               {
                   image: 'photo-1444664597500-035db93e2323-177x142.jpg',
                   testo: 'The human story of uniqueness',
                   paragrafo: 'Lorem ipsum dolor sit amet, consectetur',
                   paragrafo2: 'Lorem ipsum dolor sit amet, consectetur'
               },
               {
                   image: 'photo-1447430617419-95715602278e-177x142.jpg',
                   testo: 'Sustainable trade tactics',
                   paragrafo: 'Lorem ipsum dolor sit amet, consectetur',
                   paragrafo2: 'Lorem ipsum dolor sit amet, consectetur'
               },
               {
                   image: 'photo-1460230525622-630fe3294cd7-177x142.jpg',
                   testo: 'Farmers making a difference',
                   paragrafo: 'Lorem ipsum dolor sit amet, consectetur',
                   paragrafo2: 'Lorem ipsum dolor sit amet, consectetur'
               },
               {
                   image: 'photo-1460600421604-5e138c208b9c-177x142.jpg',
                   testo: 'Meeting remote tribes in Peru',
                   paragrafo: 'Lorem ipsum dolor sit amet, consectetur',
                   paragrafo2: 'Lorem ipsum dolor sit amet, consectetur'
               },

           ]
           
       }
   },
   components:{
       Section1,
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
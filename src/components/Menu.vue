<template>
  <div class="menu">
            <ul>
                <li v-for="(item, index) in ListMenu"
                :key="index" >
                {{item}}
                </li>
                <li class="bottone">DONATE</li>
            </ul>
        </div>
</template>

<script>
export default {
    nome: 'Menu',
    props:{
       ListMenu: Array
   },
}
</script>

<style lang="scss" scoped>

@import '../assets/vars';
@import '../assets/mixin';

ul{
    list-style: none;
    @include flex(jsaa);
    li{
        color: $color-gray;
        font-size: 10px;
        margin-right: 45px;
        cursor: pointer;
    }
    
    li:first-child{
        color: $color-orange;
    }
    li.bottone{
        color: white;
        background-color: orange;
        padding: 6px 10px;
        cursor: pointer;
    }
}

</style>
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

ul{
    list-style: none;
    display: flex;
    justify-content: space-around;
    align-items: center;
    li{
        color: white;
        font-size: 13px;
        margin-right: 20px;
        cursor: pointer;
    }
    li.bottone{
        background-color: orange;
        padding: 4px;
        cursor: pointer;
    }
}

</style>
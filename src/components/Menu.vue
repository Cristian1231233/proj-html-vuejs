<template>
  <div class="menu">
            <ul>
                <li>HOME</li>
                <li>MISSION</li>
                <li>CAUSES</li>
                <li>JOURNAL</li>
                <li class="bottone">DONATE</li>
            </ul>
        </div>
</template>

<script>
export default {
    nome: 'Menu'
}
</script>

<style lang="scss" scoped>

ul{
    list-style: none;
    display: flex;
    justify-content: space-around;
    align-items: center;
    li{
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
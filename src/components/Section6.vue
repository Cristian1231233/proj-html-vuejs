<template>
  <div class="section-6">
    <div class="text">
      <div class="title">CHANGE A LIFE TODAY</div>
      <div class="line">LINE</div>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam est distinctio molestiae molestias atque. Amet velit esse ut sint, doloribus, eaque quo earum voluptate</p>
      <button>VOLUNTEER</button>
      <button>DONATE NOW</button>
    </div>
  </div>
</template>

<script>
export default {
    nome: 'Section6'
}
</script>

<style lang="scss" scoped>

.section-6{
    
    height: 400px;
    display: flex;
    justify-content: center;
    align-items: center;
    .text{
        width: 500px;
        text-align: center;
        margin: 10px auto;
        .title, p, button{
            margin: 20px;
        }
    }
}

</style>
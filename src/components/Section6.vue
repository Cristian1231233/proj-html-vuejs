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

@import '../assets/vars.scss';

.section-6{
    height: 400px;
    color: white;
    background-image: url('../assets/images/home-footer.jpg');
    background-size: 1400px;
    background-position-x: center;
    background-position-y: center;
    display: flex;
    justify-content: center;
    align-items: center;
    .text{
        width: 500px;
        text-align: center;
        margin: 10px auto;
        .title{
            font-size: 20px;
        }
        .title, p, button{
            margin: 20px;
        }
        button{
            color: white;
            border: 1px solid white;
            background-color: transparent;
            padding: 6px 20px;
            cursor: pointer;
        }
    }
}

</style>
<template>
  <div class="section-6">
    <div class="text">
      <div class="title">CHANGE A LIFE TODAY</div>
      <div class="line"></div>
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
@import '../assets/mixin.scss';

.section-6{
    height: 400px;
    color: white;
    background-image: url('../assets/images/home-footer.jpg');
    background-size: 1400px;
    background-position-x: center;
    background-position-y: center;
    @include flex(ja);
    .text{
        width: 610px;
        text-align: center;
        margin: 10px auto;
        .title{
            font-size: 20px;
        }
        .line{
            height: 2px;
            width: 100px;
            background-color: $color-orange;
            margin: 20px auto;
        }
        .title, p, button{
            margin: 20px;
        }
        p{
            color: rgb(233, 227, 227);
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
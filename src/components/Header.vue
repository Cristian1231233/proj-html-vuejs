<template>
  <header>
    <div class="header-top">
        <div class="logo">
            <img src="../assets/images/avada-charity-logo.png" alt="">
        </div>
        <Menu />
    </div>
    <div class="container-header-bottom">
      <div class="header-bottom">
        <h1>MAKE A DIFFERENCE</h1>
        <p>As long as poverty, injustice & unequality persist, none of us can truli rest</p>
        <button>our mission</button>
        <button>donate now</button>
      </div>
    </div>
  </header>
</template>

<script>

import Menu from './Menu'

export default {
   nome: 'Header',
   components:{
       Menu
   }
}
</script>

<style lang="scss" scoped>

header{
    height: 500px;
    background-image: url('../assets/images/home-page-slider.jpg');
    background-size: 1500px;
    background-position: center;

    .header-top{
        height: 70px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        padding: 20px 40px;

        .logo{
        width: 200px;
           img{
            width: 100%;
            cursor: pointer;
        }
       }
    }
    
}
.container-header-bottom{
    height: calc(100% - 70px);
    display: flex;
    justify-content: center;
    align-items: center;

    .header-bottom{
        text-align: center;
    }
}

</style>
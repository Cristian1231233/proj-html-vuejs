<template>
  <header>
    <div class="header-top">
        <div class="logo">
            <img src="../assets/images/avada-charity-logo.png" alt="">
        </div>
        <Menu :ListMenu="ListMenu" />
    </div>
    <div class="container-header-bottom">
      <div class="header-bottom">
        <h1 class="titolo-header">MAKE A DIFFERENCE</h1>
        <p class="p-header">As long as poverty, injustice & unequality persist, none of us can truli rest</p>
        <button class="button-header">OUR MISSION</button>
        <button class="button2-header">DONATE NOW</button>
      </div>
    </div>
  </header>
</template>

<script>

import Menu from './Menu'

export default {
   nome: 'Header',
   data(){
        return{
            ListMenu:[
                'HOME',
                'MISSION',
                'CAUSES',
                'JOURNAL'
            ]
        }
    },
   components:{
       Menu
   }
}
</script>

<style lang="scss" scoped>

@import '../assets/vars.scss';

header{
    height: 600px;
    background-image: url('../assets/images/home-page-slider.jpg');
    background-size: 1350px;
    background-position: center;
    background-position-y: 1px;

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
        font-size: 20px;
        color: white;
        .titolo-header, .p-header{
            margin-bottom: 20px;
        }
        .p-header{
            font-size: 15px;
            color: #C8C9CB;
        }
        .button-header, .button2-header{
            background-color: transparent;
            margin: 15px;
            padding: 6px 10px;
            cursor: pointer;
        }
        .button-header{
            color: #C8C9CB;
            border-color: #C8C9CB;
        }
        .button2-header{
            color: $color-orange;
            border-color: $color-orange;
        }
    }
}

</style>
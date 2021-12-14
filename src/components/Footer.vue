<template>
  <footer>
      <div class="footer-top">
          <div class="logo">
              <img src="../assets/images/avada-charity-sticky-header-logo.png" alt="">
          </div>
      </div>
      <div class="footer-bottom">
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem doloremque</p>
            <div class="icon-social">
                <div class="icon" v-for="(icon, index) in iconList"
                :key="index"
                >
                    <i :class="icon"></i>
                </div>
            </div>
      </div>
      <div class="footer-end">
          <div class="arrow-under"><i class="fas fa-chevron-up"></i></div>
      </div>
  </footer>
</template>

<script>
export default {
   nome: 'Footer',
    props:{
        iconList: Array
    }
}
</script>

<style lang="scss" scoped>

@import '../assets/mixin';

.footer-top{
    @include flex(a);
    height: 90px;
    .logo{
        width: 240px;
        height: 50px;
        margin: auto;
        img{
            width: 100%;
            height: 100%;
        }
    }
}
.footer-bottom{
    @include flex(jca);
    flex-direction: column;
    height: 70px;
    background-color: rgb(243, 234, 234);
    p{
        font-size: 8px;
        margin-bottom: 15px;
    }
    .icon-social{
        width: 130px;
        height: 25px;
        @include flex(jsa);
        .icon{
            width: 25px;
            height: 100%;
            background-color:white;
            border-radius: 50%;
            text-align: center;
            line-height: 25px;
            cursor: pointer;
            
        }
    }
    
}
.footer-end{
    height: 30px;
    background-color: rgb(243, 234, 234);
    position: relative;
    
    .arrow-under{
        width: 35px;
        height: 28px;
        color: white;
        background-color: rgb(31, 30, 30);
        position: absolute;
        right: 30px;
        border-top-left-radius: 5px;
        border-top-right-radius: 5px;
        @include flex(jca);
    }
}

</style>
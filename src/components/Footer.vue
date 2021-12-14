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
                <!-- <div class="icon">
                    <i class="fab fa-instagram"></i>
                </div>
                <div class="icon">
                    <i class="fab fa-twitter"></i>
                </div>
                <div class="icon">
                    <i class="fab fa-youtube"></i>
                </div> -->
            </div>
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

.footer-top{
    display: flex;
    align-items: center;
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
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    height: 90px;
    background-color: rgb(243, 234, 234);
    p{
        font-size: 8px;
        margin-bottom: 15px;
    }
    .icon-social{
        width: 130px;
        height: 25px;
        display: flex;
        justify-content: space-around;
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

</style>
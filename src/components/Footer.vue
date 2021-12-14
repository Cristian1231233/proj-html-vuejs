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
                <div class="icon">

                </div>
            </div>
      </div>
  </footer>
</template>

<script>
export default {
   nome: 'Footer'
}
</script>

<style lang="scss" scoped>

.footer-top{
    display: flex;
    align-items: center;
    height: 90px;
    border: 1px solid black;
    .logo{
        width: 240px;
        height: 50px;
        border: 1px solid black;
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
        width: 100px;
        height: 25px;
        border: 1px solid black;
    }
}

</style>
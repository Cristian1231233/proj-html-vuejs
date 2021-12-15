<template>
  <div>
    <Header />
    <Main />
    <Footer :iconList="iconList" />
  </div>
</template>

<script>
// import HelloWorld from './components/HelloWorld.vue'
   import Header from './components/Header.vue'
   import Main from './components/Main.vue'
   import Footer from './components/Footer.vue'

export default {
  name: 'App',
  data(){
    return{
      iconList: [
          'fab fa-facebook-f',
          'fab fa-instagram',
          'fab fa-twitter',
          'fab fa-youtube'
      ],
      
      
    }
  },
  components: {
     Header,
     Main,
     Footer
  }
}
</script>

<style lang="scss">

@import url('https://fonts.googleapis.com/css2?family=Acme&family=Montserrat:wght@300&display=swap');

*{
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body{
  font-family: 'Montserrat', sans-serif;
}
</style>


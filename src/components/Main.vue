<template>
  <div class="main">
      <div class="section-1">
          <div class="section-1-left">
              <div>EVERY MOMENT COUNTS</div>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Illum recusandae tenetur at, perferendis id quos ipsa. Sequi alias perferendis, quos pariatur incidunt, neque similique velit sapiente quas corporis, delectus vitae.</p>
              <button>OUR MISSION</button>
          </div>
          <div class="section-1-right">
              <div class="container-1">
                  <div class="num-text">
                    <div>2032</div>
                    <div>Volunters worldwide</div>
                  </div>
                  <div class="num-text">
                    <div>132</div>
                    <div>Active projects</div>
                  </div>
                  <div class="num-text">
                    <div>3.8M</div>
                    <div>Donated</div>
                  </div>

              </div>
          </div>
      </div>
  </div>
</template>

<script>
export default {
   nome: 'Main'
}
</script>

<style lang="scss" scoped>

.main{
    min-height: 400px;
    .section-1{
        display: flex;
        height: 350px;
        background-color: red;
        .section-1-left{
            height: 100%;
            width: 70%;
            background-color: white;
            padding: 45px;
            p{
                margin: 10px;
            }
            button{
                margin: 10px 10px;
            }
            
        }
        .section-1-right{
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100%;
            width: 30%;
            text-align: center;
            color: white;
            background-color: rgb(243, 52, 52);
            .num-text{
                margin: 20px;
                font-size: 18px;
            }
        }
    }
}

</style>
<template>
  <div id="app">
      <div class="header-container">
          <div class="nav-bar">
            <div class="image">
                <img src="..\img-header\dark-logo.png" alt="">
            </div>
            <div class="list">
                <ul>
                    <li>Home</li>
                    <li>Pages</li>
                    <li>Courses</li>
                    <li>Features</li>
                    <li>Blog</li>
                    <li>Shop</li>
                </ul>
            </div>
              
          </div>
      </div>
    
    
  </div>
</template>

<script>



export default {
  name: 'App',
  components: {
   
  }
}
</script>

<style lang="scss">
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  
}
.header-container{
    width: 100vw;
    height: 78px;
    display: flex;
    justify-content: center;
    

    .nav-bar{
        
        width: 1170px;
        display: flex;
        justify-content: space-between;
            
        img{
            width: 160px;
        }
        .list{
            display: flex;

            ul{
            list-style: none;
            display: flex;
            align-items: center;
            justify-content: center;

            li{
                display: flex;
                padding: 5px;
            }
            }
        }

        

    }
}


</style>

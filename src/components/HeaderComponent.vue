<template>
  <div id="app">
      <div class="header-container">
          <div class="nav-bar">
            <div class="image">
                <img src="../assets/img-header/dark-logo.png" alt="">
            </div>
            <div class="list">
                <ul>
                    <li><a href="#">Home<i class="fa-solid fa-angle-down"></i></a></li>
                    <li><a href="#">Pages<i class="fa-solid fa-angle-down"></i></a></li>
                    <li><a href="#">Courses<i class="fa-solid fa-angle-down"></i></a></li>
                    <li><a href="#">Features<i class="fa-solid fa-angle-down"></i></a></li>
                    <li><a href="#">Blog<i class="fa-solid fa-angle-down"></i></a></li>
                    <li><a href="#">Shop<i class="fa-solid fa-angle-down"></i></a></li>
                    <i class="far fa-user-circle user"></i>
                </ul>
                <div class="search-container">
                    <input type="text" placeholder="Search..." class="input-search">
                    <i class="fas fa-search ricerca"></i>

                </div>
                
                
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
            margin-top: 28px;
            width: 160px;
        }
        .list{
            display: flex;
            

            ul{
                margin-top: 25px;
                list-style: none;
                display: flex;
                align-items: center;

                i{
                    cursor: pointer;
                   
                    &:hover{
                        color: #25ab94;
                    }
                }
                
                .user{
                        font-size: 20px;
                        padding-right: 10px;
                    }

                li{
                    display: flex;
                    padding: 20px;

                    a{
                        color: #0b0b0b;
                        text-decoration: none;

                        &:hover{
                        color: #25ab94;
                        text-decoration: underline;
                    }

                        i{
                            padding: 3px;
                        }
                    }

                    
                }

            
            }
            .search-container{
                display: flex;
                align-items: center;
                position: relative;

                .ricerca{
                    color: #25ab94;
                    position: absolute;
                    right: 10px;
                }

                .input-search{
                background-color: #f6f3f5;
                border: none;
                border-radius: 8px;
                padding: 15px;

                    ::placeholder { 
                    color: #9ea4a5;
                    }

                    
                }
            }
        }

        

    }
}


</style>

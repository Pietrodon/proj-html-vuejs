<template>
<div id="app">
    <div class="container-courses">
        <div class="content-courses">
            <div class="title-text">
                <p>STIMULATED TO LEARN?</p>
                <h2>Featured Online Courses</h2>
            </div>
            <div class="card-courses">
                <div class="card">
                    <img src="../assets/img-courses/course-02-480x298.jpg" alt="">

                </div>
            </div>
            <div>
                <button @click="richiamo()">
                    View all courses 
                    <i class="fas fa-arrow-right arrow"></i>
                </button>
            </div>
        </div>
        
    </div>

</div>
    
</template>

<script>


export default {
  name: 'App',
  components: {
   
  },
  methods:{
      richiamo:function(){
          alert('Stai per essere reindirizzato ai nostri corsi')
      }
  }

  
}
</script>

<style lang="scss">
.container-courses{
    background-color: #F5F7FA;
    width: 100vw;
    height: 1140px;
    display: flex;
    justify-content: center;

    .content-courses{
        width: 1170px;
        display: flex;
        flex-direction: column;
        align-items: center;
        

        .title-text{
            height: 70px;
            width: auto;
            margin-top: 50px;
            
            p{
                color: #aeadae;
                margin-left: 20%;
                
            }

            h2{
                color: #48495f;
                font-size: 30px;
                margin: 0;
                

            }
        }

        .card-courses{
            width: 1084px;
            height: 652px;
            border: 1px solid red;
            margin-top: 25px;

            .card{
                width: 522px;
                height: 172px;
            }
        }



        button{
            margin-top: 25px;
            background-color: #25ab94;
            border: none;
            color: #ffffff;
            padding: 10px;
            border-radius: 5px;
            font-weight: 800;
            width: 257px;

            &:hover{
            background-color: #3F3A64;
            cursor: pointer;
        }
            .arrow{
                margin-left: 5px;
            }
        }
        
    }
}

</style>
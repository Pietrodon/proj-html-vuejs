<template>
<div id="app">
    <div class="container-courses">
        <div class="content-courses">
            <div class="title-text">
                <p>STIMULATED TO LEARN?</p>
                <h2>Featured Online Courses</h2>
            </div>
            <div class="card-courses">
                <div class="card-size">
                    <div class="card">
                        <img src="../assets/img-courses/course-02-480x298.jpg" alt="" class="card-img">
                    </div>
                    <div class="course-info">
                        <p class="price">$40.00</p>
                        <h2 class="course-name">Learning to Write as a Professional Author</h2>
                        <p class="class-info"><i class="far fa-file-alt first-icon"></i>20 Lessons <i class="far fa-user second-icon"></i>50 Student</p>
                    </div>
                </div>
                <div class="card-size">
                    <div class="card">
                        <img src="../assets/img-courses/stock-full-hd-03-480x298.jpg" alt="" class="card-img">
                    </div>
                    <div class="course-info">
                        <p class="price">Free</p>
                        <h2 class="course-name">Customer-centric Info-Tech Strategies</h2>
                        <p class="class-info"><i class="far fa-file-alt first-icon"></i>24 Lessons <i class="far fa-user second-icon"></i>769 Student</p>
                    </div>
                </div>
                <div class="card-size">
                    <div class="card">
                        <img src="../assets/img-courses/stock-full-hd-04-480x298.jpg" alt="" class="card-img">
                    </div>
                    <div class="course-info">
                        <p class="price">$19.00</p>
                        <h2 class="course-name">Open Programming Courses for Everyone: Python</h2>
                        <p class="class-info"><i class="far fa-file-alt first-icon"></i>17 Lessons <i class="far fa-user second-icon"></i>62 Student</p>
                    </div>
                </div>
                <div class="card-size">
                    <div class="card">
                        <img src="../assets/img-courses/stock-full-hd-06-480x298.jpg" alt="" class="card-img">
                    </div>
                    <div class="course-info">
                        <p class="price">$26.00</p>
                        <h2 class="course-name">Academy Listening and Note-taking</h2>
                        <p class="class-info"><i class="far fa-file-alt first-icon"></i>14 Lessons <i class="far fa-user second-icon"></i>67 Student</p>
                    </div>
                </div>
                <div class="card-size">
                    <div class="card">
                        <img src="../assets/img-courses/course-featured-image-01-480x298.jpg" alt="" class="card-img">
                    </div>
                    <div class="course-info">
                        <p class="price">$39.00</p>
                        <h2 class="course-name">Master jQuery in a Short Period of Time</h2>
                        <p class="class-info"><i class="far fa-file-alt first-icon"></i>6 Lessons <i class="far fa-user second-icon"></i>51 Student</p>
                    </div>
                </div>
                <div class="card-size">
                    <div class="card">
                        <img src="../assets/img-courses/stock-full-hd-05-480x298.jpg" alt="" class="card-img">
                    </div>
                    <div class="course-info">
                        <p class="price">$59.00</p>
                        <h2 class="course-name">Introduction to Javascript for Beginners</h2>
                        <p class="class-info"><i class="far fa-file-alt first-icon"></i>14 Lessons <i class="far fa-user second-icon"></i>76 Student</p>
                    </div>
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
    display: flex;
    justify-content: center;
    padding-bottom: 40px;

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
            margin-top: 25px;
            display: flex;
            flex-wrap: wrap;
            
            .card-size{
                width: 522px;
                height: 172px;
                display: flex;
                margin: 0 20px 35px 0;
                

                &:hover{
                    background-color: #ffffff;
                    cursor: pointer;
                    border-radius: 28px;
                    
                }

                .course-info{
                    width: 323px;
                    height: 133px;
                    margin-left: 5%;
                    
                    .price{
                        font-size: 25px;
                        color: #25ab94;
                        font-weight: 900;
                        margin-bottom: -15px;
                    }
                    .course-name{
                        color: #3F3A64;
                        
                        &:hover{
                            color: #25ab94;
                        }
                        
                    }
                    .class-info{
                        font-size: 13px;
                        color: #9996AC;

                        .first-icon{
                            padding-right: 10px;
                        }

                        .second-icon{
                            padding:0 10px 0 10px;
                        }
                    }
                }

                .card{
                width: 170px;
                height: 170px;

                    .card-img{
                        border-radius: 50%;
                        width: 100%;
                        height: 100%;
                        object-fit: cover;
                     }
                }
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
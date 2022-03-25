<template>
  <div id="app">
      <div class="external-cc">
          <div class="title-carousel">
            <p class="description-carousel">GREAT WORDS ABOUT MAXCOACH</p>
            <h2 class="name-carousel">
              Our 
              <span>top learners'</span>
              vebatim
            </h2>
            
          </div>
          <div class="carousel">
            <div class="card-carousel non-active">
              <div class="description-carousel">
                <h3 class="title-description">It's a choice of quality for people width special needs</h3>
                <p class="text-description">I'm a very strict person so I require everything to be organized and neat. Then,I'll be able to make things right and shine. MaxCoach guys just got me</p>
              </div>
              <div class="profile-carousel">
                <img src="../assets/profile-carousel/testimonial-avata-03.jpg" alt="" class="img-profile">
                <div class="profile-info">
                  <h3 class="name-profile">FLORENCE THEMES</h3>
                  <p class="job-profile">/Multimedia Admin</p>
                </div>               
              </div>
            </div>
            
            <div class="card-carousel active">
              <div class="description-carousel">
                <h3 class="title-description">High level of effiency and scientific teaching methods</h3>
                <p class="text-description">I am free to learn at my own pace, follow my own schedule and choose the subject I want to learn from the syllabus. Great study portal fro people like me. </p>
              </div>
              <div class="profile-carousel">
                <img src="../assets/profile-carousel/testimonial-avata-02.jpg" alt="" class="img-profile">
                <div class="profile-info">
                  <h3 class="name-profile">MINA HOLLACE</h3>
                  <p class="job-profile">/Freelancer</p>
                </div>                
              </div>
            </div>

            <div class="card-carousel non-active">
              <div class="description-carousel">
                <h3 class="title-description">Professional team of Specialists and passionate mentors at reach</h3>
                <p class="text-description">I need to get a certification for English proficiency and MaxCoach is my best choice. Their tutors are smart and professional when dealing with students</p>
              </div>
              <div class="profile-carousel">
                <img src="../assets/profile-carousel/testimonial-avata-04.jpg" alt="" class="img-profile">
                <div class="profile-info">
                  <h3 class="name-profile">MADLEY PONDOR</h3>
                  <p class="job-profile">/IT Specialist</p>
                </div> 
              </div>

            </div>
          </div>
          <div class="online">
            <p>
              Start today for getting 
              <span>
                Online Certification
              </span>
            </p>
            <h2>You can be your own guiding star with our help!</h2>
            <button>
              Get started now
            </button>
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
    .external-cc{
      background-color: #F5F7FA;
      width: 100vw;
      display: flex;
      flex-direction: column;
      align-items: center;

      .title-carousel{
        width: 1170px;
        height: max-content;
        margin-top: 35px;
        text-align: center;

        .description-carousel{
          color: #aeadae;
          
        }
        .name-carousel{
          font-size: 30px;
          margin-top: 5px;
          color: #48495f;

          span{
            color: #25ab94;
          }
        }
        
        
      }

      .active{
        &:hover{
          cursor: pointer;
        }
      }

      .non-active{
        opacity: 0.4;

        &:hover{
          opacity: 1;
          cursor: pointer;
        }
      }

      .carousel{
        width: 100vw;
        height: max-content;
        display: flex;
        justify-content: center;
        align-items: center;
        

        .card-carousel{
          width: 574px;
          height: max-content;
          display: flex;
          flex-direction: column;
          align-items: center;
          background-color: #ffffff;
          margin: 20px;
          padding: 20px;

          .description-carousel{
            width: 440px;
            height: max-content;

            .title-description{
              color: #48495f;
              font-size: 20px;
            }
            .text-description{
              color: #aeadae;
              font-size: 20px;
            }
          }
          .profile-carousel{
            display: flex;
            width: 440px;

            .img-profile{
              border-radius: 50%;
              width: 70px;
              height: 70px;
              
            }
            .profile-info{
              margin: -15px 0 0 15px;

              .name-profile{
                font-size: 15px;
                color: #48495f;
              }

              .job-profile{
                font-size: 15px;
                color: #aeadae;

              }


            }
          }
        }
      }
      .online{
        text-align: center;
        padding: 50px;

        p{
          color: #48495f;
          font-size: 20px;
          font-weight: 800;

          span{
            color: #25ab94;
            font-weight: 100;
          }

        }
        h2{
            color: #48495f;
            font-size: 30px;
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
            background-color:#3F3A64 ;
            cursor: pointer;
          }
        }
      }
    }



</style>

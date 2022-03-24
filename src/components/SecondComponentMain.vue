<template>
  <div id="app">
      <div class="container-2nd">
        <div class="content-2nd">
            <div class="title-text-2nd">
                <p>MAXCOACH AVAILABLE COURSES</p>
                <h2>Access <span class="color-title">Smart Tutoring</span> Program For Begefits.</h2>
            </div>
            <div class="container-2nd">
                <div class="img-text">
                    <img src="../assets/ho-finito-la-fantasia/home-2-image-box-01.png" alt="">
                    <h3 class="title-2nd">Customize Preferences</h3>
                    <p class="description">Learners are given the right to arrange and customize their study schedule and timetable based on preferences</p>
                    <p class="link">
                        <a href="#">
                           Start here
                          <i class="fas fa-arrow-right arrow"></i>
                        </a>
                    </p>
                </div>
                <div class="img-text">
                    <img src="../assets/ho-finito-la-fantasia/about-us-02-image-box-02.png" alt="">
                    <h3 class="title-2nd">Cloud Storage</h3>
                    <p class="description">You can store online lessons via online cloud or download to you device and revise lessons pn the way.</p>
                    <p class="link">
                        <a href="#">
                           Get Free Quote
                          <i class="fas fa-arrow-right arrow"></i>
                        </a>
                    </p>
                </div>
                <div class="img-text">
                    <img src="../assets/ho-finito-la-fantasia/home-2-image-box-03.png" alt="">
                    <h3 class="title-2nd">Multimedia Channels</h3>
                    <p class="description">We provide study materials with various formats:video,audio,slides,doc,prints,books and applications</p>
                    <p class="link">
                        <a href="#">
                           Start now
                          <i class="fas fa-arrow-right arrow"></i>
                        </a>
                    </p>
                </div>
            </div>
            
        </div>
        <div class="video-text">

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
.container-2nd{
    width: 100vw;
    display: flex;
    justify-content: center;
    padding-bottom: 40px;
    

    .content-2nd{
        width: 1170px;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        
        

        .title-text-2nd{
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

                .color-title{
                    color: #25ab94;
                }
                

            }
        }

            .img-text{
                width: 345px;
                height: 370px;
                margin: 65px 25px 25px 0;
                

                .title-2nd{
                    font-size: 30px;
                    color: #48495f;
                    margin-bottom: 0;
                }
                .description{
                    font-size: 20px;
                    color: #aeadae;
                }
                .link a{
                    color: #aeadae;
                    text-decoration: none;
                    font-weight: 900;

                    &:hover{
                        color: #25ab94;
                        text-decoration: underline;
                    }
                }

            }

        


    }
}
</style>

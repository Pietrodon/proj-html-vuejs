<template>
<div id="app">
    <div class="container">
        <div class="main-content">
            <div class="content">
                <div class="text-button">
                    <h1>Distant learning for further expansion</h1>
                    <p class="description">
                        Learning is a life-long journey that in fact we never find the terminate stop. Stop searching, enjoy the preocess.
                    </p>
                    <button class="button-dowload" @click="download()">
                        <span><i class="fas fa-download button"></i></span> 
                        Download free guide
                    </button>
                    <p class="question">Have question?
                        <span><a href="#" class="question">Get free sample</a></span>
                    </p>
                </div>
                <div class="main-image">
                    <img src="../assets/img-header/about-me-profile.jpg" alt="" class="profile-img">
                    <img src="../assets/img-header/maxcoach-shape-07-150x150.png" alt="" class="bg-image-2">
                    <img src="../assets/img-header/maxcoach-shape-08.png" alt="" class="bg-image-1">
                    <img src="../assets/img-header/maxcoach-shape-02.png" alt="" class="bg-image-3">
                    
                </div>
            </div>
            <div class="client-img">
                <img src="../assets/img-header/client-logo-01.png" alt="">
                <img src="../assets/img-header/client-logo-02.png" alt="">
                <img src="../assets/img-header/client-logo-03.png" alt="">
                <img src="../assets/img-header/client-logo-04.png" alt="">
                <img src="../assets/img-header/client-logo-05.png" alt="">
                <img src="../assets/img-header/client-logo-06.png" alt="">
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
      download: function(){
          alert('Download in corso...')
      }
  }

  
}
</script>

<style lang="scss">
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;

    .main-content{
        width: 1170px;
        
        .client-img{
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 40px;
        }
        .client-img img{
            padding: 40px;
            opacity: 0.5;

            &:hover{
                opacity: 1;
            }
        }
        
        .content{
            width: 1290px;
            height: 570px;          
            margin-top: 40px;
            display: flex;
            justify-content: space-between;

            .text-button{
                width: 456px;
                display: flex;
                flex-direction: column;
                justify-content: center; 

                h1{
                    font-size: 50px;
                    color: #48495f;
                    margin: 0;
                }
                .description{
                    font-size: 20px;
                    color: #aeadae;
                }
                .button-dowload{
                    background-color: #25ab94;
                    border: none;
                    color: #ffffff;
                    padding: 10px;
                    border-radius: 5px;
                    font-weight: 800;
                    width: 257px;

                    .button{
                        padding: 3px;
                        margin-right: 2px;
                        font-size: 15px;
                    }

                     &:hover{
                         background-color: #3F3A64;
                         cursor: pointer;
                     }
                }
                .question{
                    color: #aeadae;
                    font-size: 15px;

                    a{
                        color: #25ab94;
                        font-weight: 800;
                        text-decoration-color: #aeadae;  
                    }
                }
            }
            .main-image{
                position: relative;
                
                
                .profile-img{
                    z-index: 22;
                    border-radius: 100%;
                    width: 85%;
                    height: 85%;
                    margin-top: 15px;
                    position: relative;
                    
                }

                .bg-image-1{
                    z-index: 0;
                    position: absolute;
                    top: 25%;
                    right: 85%;
                    height: 200px;
                }
                .bg-image-2{
                    position: absolute;
                    top: 65%;
                    right: 15%;
                    z-index: 0;
                }
                .bg-image-3{
                    position: absolute;
                    width: 100px;
                    height: 100px;
                    top: 15%;
                    left: 82%;
                }
            }
        }
    }
}

</style>

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
        height: 570px;


        .client-img{
            display: flex;
            justify-content: center;
            align-items: center;
            margin-top: 40px;
        }
        .client-img img{
            padding: 40px;
            opacity: 0.5;
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
                    }

                    // :hover{
                    //     background-color: #3F3A64;
                    // }
                }
                .question{
                    color: #aeadae;
                    font-size: 15px;

                    a{
                        color: #25ab94;
                        font-weight: 800;  
                    }
                }
            }
            .main-image{


                .profile-img{
                    
                    border-radius: 100%;
                    width: 570px;
                    height: 570px;
                }
            }
        }
    }
}

</style>

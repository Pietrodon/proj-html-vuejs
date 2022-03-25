<template>
  <div id="app">
      <div class="external-footer">
          <div class="footer">
              <div class="address">
                  <h3 class="title-address">Address</h3>
                  <p>382 NE 191st # 87394 Miami,FL 33179-3899</p>
                  <p>+1(305) 547-9909 (9am - 5pm EST,Monday - Friday)</p>
                  <p>support@maxcoach.com</p>
                  <div class="social-icon">
                      <i class="fab fa-facebook-square"></i>
                      <i class="fab fa-twitter"></i>
                      <i class="fab fa-instagram"></i>
                      <i class="fab fa-linkedin"></i>
                  </div>


              </div>
              <div class="explore">
                    <h3 class="title-address">Explore</h3>  
                    <div class="list">
                        <div class="first">
                            <ul>
                                <li>Start here</li>
                                <li>Blog</li>
                                <li>About us</li>
                            </ul>
                        </div>
                        <div class="second">
                            <ul>
                                <li>Success story</li>
                                <li>Courses</li>
                                <li>Contact us</li>
                            </ul>
                        </div>
                    </div>
              </div>
              <div class="information">
                  <h3 class="title-address">Information</h3>
                  <ul>
                      <li>Membership</li>
                      <li>Purchase guide</li>
                      <li>Privacy policy</li>
                      <li>Terms of services</li>

                  </ul>

              </div>
            </div>
            <div class="copyright">
                <p>
                    <i class="far fa-copyright"></i>
                    2020 Maxcoach. All Rights Reserved
                </p>

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
    .external-footer{
        width: 100vw;
        height: max-content;
        background-color: #F5F7FA;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;


        .footer{
            width: 1170px;
            display: flex;
            justify-content: center;
            align-items: center;
            

            .address{
                width: 340px;
                height: 180px;
                flex-grow: 1;
                color: #696969;
                padding: 15px;

                .title-address{
                    font-weight: 800;
                    color: #48495f;
                }

                .social-icon{
                    font-size: 25px;

                    i{
                        padding-right: 20px;
                    }
                    
                }
                
                
            }
            .explore{
                width: 220px;
                height: 180px;
                flex-grow: 1;

                .list{
                    display: flex;
                    

                    .first{
                        margin-top: -20px;
                        flex-grow: 1;
                    }
                    .second{
                        margin-top: -20px;
                        flex-grow: 1;
                        
                    }
                    
                    ul{
                        color: #696969;
                        list-style: none;
                        padding: 0;

                        li{
                            padding-bottom: 15px;
                        }
                    }
                }
            }
            .information{
                width: 120px;
                height: 180px;
                flex-grow: 1;

                .title-address{
                    font-weight: 800;
                    color: #48495f;
                }

                ul{
                    color: #696969;
                    list-style: none;
                    padding: 0;

                    li{
                        padding-bottom: 15px;
                    }
                }
            }
        }
        .copyright{
                width: 100%;
                height: max-content;
                padding: 15px;
                display: flex;
                justify-content: center;
                color: #aeadae;
                
            }
    }



</style>

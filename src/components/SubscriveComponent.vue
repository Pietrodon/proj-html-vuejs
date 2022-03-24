<template>
  <div id="app">
      <div class="container-subscrive">
          <div class="content-subscrive">
              <div class="text-subscribe">
                <h2>
                  Subscribe
                  <span>Newsletters</span>
              </h2>
              <p>Enter your email address to register to our newsletter subscription delivered on a regular basis!</p>
              </div>
              <input type="email" placeholder="Enter your email">
                <div class="sub">
                  <button>Subscrive</button>
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
.container-subscrive{
    width:100vw;
    height: 400px;
    display: flex;
    justify-content: center;

    .content-subscrive{
        width: 1170px;
        height: 100%;
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;

        .text-subscribe{
            width: 450px;
            height: max-content;
            text-align: center;

            h2{
                color: #48495f;
                font-weight: 800;

                span{
                    color: #25ab94;
                }
            }
            p{
                color: #aeadae;
                font-weight: 800;
            }


        }

        input{
           background-color: #f6f3f5;
           border: none;
           border-radius: 8px;
           padding: 15px;
           width: 25%;
           margin-top: 5%;
           position: relative;
        }
        .sub{
            width: max-content;
            height: max-content;

            button{
                background-color: #25ab94;
                color: #ffffff;
                font-weight: 800;
                border: none;
                position: absolute;
                top: 15px;
            }

        }
    }
}



</style>

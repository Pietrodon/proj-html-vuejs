<template>
  <div id="app">
      <div class="container-external">
          <div class="number-list">
              <div class="card-number-external">
                  <div class="card-number">
                    <h3>Successfully Trained</h3>
                    <h2>1790</h2>
                    <p>ENROLLED LEARNERS</p>
                  </div>
                  <div class="card-number">
                    <h3>Proudly Received</h3>
                    <h2>19</h2>
                    <p>COUNTRYWIDE AWARDS</p>
                  </div>
                  <div class="card-number">
                    <h3>Firmly Established</h3>
                    <h2>24</h2>
                    <p>LOCAL BRANCHES</p>
                  </div>
                  <div class="card-number">
                    <h3>Getting Featured on</h3>
                    <h2>1090</h2>
                    <p>BLOG POSTS</p>
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
.container-external{
    width: 100vw;
    display: flex;
    justify-content: center;

    .number-list{
        width: 1170px;

        .card-number-external{
            display: flex;
        }

        .card-number{
            width: 300px;
            height: 400px;
            border: 1px solid rgba($color: #aeadae, $alpha: 0.7);
            text-align: center;
            display: flex;
            flex-direction: column;
            justify-content: center;

            h3{
                color: #48495f;
                font-size: 20px;
                font-weight: 800;
            }
            h2{
                color: #25ab94;
                font-size: 40px;
                font-weight: 900;
            }
            p{
                color: #aeadae;
                font-weight: 800;
            }
        }
    }
}



</style>
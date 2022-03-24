<template>
  <div id="app">
      <div class="blog-external">
          <div class="blog-container">
              <div class="blog-description">
                <div class="blog-text">
                  <p>ENJOYABLE INSIGHTS</p>
                  <h2>
                      Most Viewed 
                      <span>Best Blogs</span>
                  </h2>
                  <p class="list"><i class="fas fa-arrow-right"></i> Become a Better Blogger: Content Plannig</p>
                  <p class="list"><i class="fas fa-arrow-right"></i> Promoting Your Online Business on Pinterest</p>
                  <p class="list"><i class="fas fa-arrow-right"></i> Gamification and Game-Based Learning</p>
                  <p class="list"><i class="fas fa-arrow-right"></i> Designing an Online Course from Expert's Perspective</p>
                  <p class="list"><i class="fas fa-arrow-right"></i> Why Online Courses Are the Future of Education</p>

                </div>
              </div>
              <div class="blog-card">
                  <div class="card-img">
                      <img src="../assets/blog-img/artist-blog-03-480x352.jpeg" alt="">
                  </div>
                  <div class="card-text">
                      <p class="jobs">ARTIST</p>
                      <h3>Brush strokes Energize Trees in Paintings</h3>
                      <p>
                        <i class="far fa-calendar"></i>
                        May 15,2020
                        <i class="far fa-eye"></i>
                        688 views
                      </p>
                  </div>
              </div>
                            <div class="blog-card">
                  <div class="card-img">
                      <img src="../assets/blog-img/artist-blog-01-480x352.jpg" alt="">
                  </div>
                  <div class="card-text">
                      <p class="jobs">ARTIST</p>
                      <h3>Pocket-Sized Notebooks Hold Minature Paintings</h3>
                      <p>
                        <i class="far fa-calendar"></i>
                        May 15,2020
                        <i class="far fa-eye"></i>
                        603 views
                      </p>
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
.blog-external{
    background-color: #F5F1ED;
    width: 100vw;
    height: 500px;
    display: flex;
    justify-content: center;

    .blog-container{
        display: flex;
        width: 1170px;

        .blog-description{
            width: 400px;
            height: 500px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            margin-left: 15px;

            .blog-text{
                
                p{
                    color: #aeadae;
                    font-weight: 800;
                }
                h2{
                    color: #48495f;
                    font-size: 30px;
                    font-weight: 800;
                    
                    span{
                        color: #25ab94;

                    }
                }
                .list{
                    color: #48495f;
                    font-weight: 800;
                }
            }
        }

        .blog-card{
            width: 300px;
            height: 400px;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            margin:45px 0 0 25px;
            background-color: #ffffff;
            border-radius: 28px;

            .card-img{
                height: 400px;
                img{
                    width: 100%;
                    border-radius: 28px 28px 0 0;
                    
                }
            }
            .card-text{
                margin-left: 15px;

                .jobs{
                    color: #aeadae;
                    font-weight: 800;

                    &:hover{
                        color: #25ab94;
                        cursor: pointer;
                    }
                }
                p{
                    color: #aeadae;

                    i{
                        padding: 0 10px 0 10px;
                    }
                }
                h3{
                    color: #48495f;
                    font-weight: 800;
                    
                    &:hover{
                        color: #25ab94;
                        cursor: pointer;
                    }
                }
            }
        }
    }
}



</style>

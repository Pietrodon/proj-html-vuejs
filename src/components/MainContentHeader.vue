<template>
<div id="app">
    <div class="container">
        <div class="main-content">
            <div class="content">
                <div class="text-button">
                    <h1>Distant learning for further expansion</h1>
                    <p>Learning is a life-long journey that in fact we never find the terminate stop. Stop searching, enjoy the preocess.</p>
                </div>
                <div class="main-image">
                    <img src="..\img-header\about-me-profile.jpg" alt="" class="profile-img">

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
.container{
    display: flex;
    justify-content: center;
    align-items: center;
    width: 100vw;

    .main-content{
        width: 1170px;
        height: 842px;
        
        .content{
            width: 1290px;
            height: 570px;
            border: 1px solid red;
            margin-top: 40px;
            display: flex;

            .text-button{
                width: 456px; 
            }
            .main-image{

                .profile-img{
                    border-radius: 100%;
                }
            }
        }
    }
}

</style>

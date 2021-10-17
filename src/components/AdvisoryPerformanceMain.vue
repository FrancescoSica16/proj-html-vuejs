<template>
  <section id="performance">
      
      <div class="container">
          <div class="row">
              <div  class="col-9 m-auto ">
                <div class="pre-titol  text-center">what are we doing</div>
                <h1 class="text-center titol-dark"> Advisory<strong>Performance</strong></h1> 
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis, dolores iusto perferendis autem excepturi rerum, nesciunt.</p>               
              </div>
              <div class="row">
                <div class="col-9 m-auto">
                  <img src="../assets/img/video-1.jpg" alt="">
                </div>
                
              </div>
              
          </div>
      </div>
  </section>
</template>

<script>
export default {
  name: "AdvisoryPerformanceMain",
  props: [],

  data: function() {
    return{
      
    }
  }
}
</script>

<style scoped lang="scss">
@import "../style/general.scss";
@import "../style/variabiles.scss";

#performance{
    background-color: white;
    
    margin: 50px 0;

    img{
      width: 100%;
    }
}
.titol-dark{
  color: black;

  strong{
    color:#048383;
  }

  p{
    color: $paragGray;
  }
}
</style>
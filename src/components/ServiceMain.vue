<template>
  <section id="service">
      <div class="container">
          <div class="row">
              <div class="col-9 m-auto d-flex align-items-end">
                <div class="service-titol">                  
                  <div class="pre-titol ">what are we doing</div>
                  <h1 class=" titol-dark"> Excellence in <strong>Services</strong></h1> 
                  <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Debitis, dolores iusto perferendis autem excepturi rerum, nesciunt.</p>  
                </div> 
                <div>
                  <button class="btn my_button_secondary ">SEE ALL</button>
                </div>
                
                                                
             </div>            
          </div>
      </div>

  </section>
</template>

<script>
export default {
  name: "ServiceMain",
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

#service{
    background-color: black;

    p{
      color: white;
    }
    button{
     margin-bottom: 20%;
    }

    .service-titol{
      width: 80%;
    }
}


</style>
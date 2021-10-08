<template>
  <section id="results">
     
      <div class="container">
          <div class="row">
              <div  class="col-9 m-auto my-5">
                <div class="pre-titol text-center">what are we doing</div>
                <h1 class="text-center"><strong>Results</strong> in Numbers</h1>                
              </div>
          </div>
      </div>
      <div class="container">
          <div class="row">
            <div class="col-10 d-flex justify-content-around m-auto">
                <div class="card text-center" 
                v-for="(results, index) in result" :key="index">
                    <div id="results-value">{{results.value}}</div>
                    <div id="results-name">{{results.nameData}}</div>
                </div> 
            </div>
          </div>
      </div>
  </section>
</template>

<script>
export default {
  name: "ResultsInNumbersMain",
  props: [],

  data: function() {
    return{
      result:[
        {
            nameData: "Certifications",
            value: "128"
        },
         {
            nameData: "Employees",
            value: "230"
        },
         {
            nameData: "Customers",
            value: "517"
        },
         {
            nameData: "Countries Served",
            value: "94"
        },
      ]
    }
  }
}
</script>

<style scoped lang="scss">
@import "../style/general.scss";
@import "../style/variabiles.scss";

#results{
    background-image: url(../assets/img/bg-1.jpg);
    height: 500px;
    background-size: cover;
}
#results-value{
    font-weight: 700;
    font-size: 1.8rem;
    color: $secondaryColor ;
    margin-bottom: 10px;
}
#results-name{
    font-weight: 800;
    color: $primarycolor;
    font-size: 1.4rem;
}
.card{
    width: calc(100% / 4);
    background-color: transparent;
    border: transparent;
}
</style>
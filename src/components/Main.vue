<template>
  <main>
    <AdvisoryPerformanceMain/>

    <ResultsInNumbersMain/>

    <ServiceMain/>

  </main>
</template>

<script>
import AdvisoryPerformanceMain from "./AdvisoryPerformanceMain.vue";
import ResultsInNumbersMain from "./ResultsInNumbersMain.vue";
import ServiceMain from "./ServiceMain.vue";

export default {
  name: "Main",
  props: [],
  components: {
    AdvisoryPerformanceMain,
    ResultsInNumbersMain,
    ServiceMain,
  },
  data: function() {
    return{
      
    }
  }
}
</script>

<style scoped lang="scss">
@import "../style/general.scss";
@import "../style/variabiles.scss";
</style>
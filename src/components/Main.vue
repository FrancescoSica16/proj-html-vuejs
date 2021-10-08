<template>
  <main>
    <AdvisoryPerformanceMain/>

    <ResultsInNumbersMain/>

    <AdvisoryPerformanceMain/>

  </main>
</template>

<script>
import AdvisoryPerformanceMain from "./AdvisoryPerformanceMain.vue";
import ResultsInNumbersMain from "./ResultsInNumbersMain.vue"
export default {
  name: "Main",
  props: [],
  components: {
    AdvisoryPerformanceMain,
    ResultsInNumbersMain,
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
<template>
  <footer>
   
    <FooterCardGroup />
  </footer>
</template>

<script>

import FooterCardGroup from "./FooterCardGroup.vue";

export default {
  name: "Footer",
  props: [],
  components: {
    FooterCardGroup,
    
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

footer{
  height: 500px;
  background-image: url(../assets/img/bg-7.jpg);
  background-repeat: no-repeat;
  background-size: cover;
  background-position-y: center;
}
</style>
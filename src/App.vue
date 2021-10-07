
<template>
  <div id="app">  

    <Header/>

    <Main/>

    <Footer/>
  </div>
</template>

<script>
import Header from './components/Header.vue';
import Main from './components/Main.vue';
import Footer from './components/Footer.vue';

export default {
  name: 'App',
  props: [],
  components: {
    Header,
    Main,
    Footer
  },
  data: function() {
    return{

    }
  },
}
</script>


<style lang="scss">
// verificare se aggiungere scope
@import "style/general.scss";
@import "style/variabiles.scss";


</style>


<template>
  <div id="app" class="container-fluid">  

    <div class="row">
      <div class="col-12">
        <Header/>
      </div>    
    </div>
    

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

*{
  margin:0;
}
</style>

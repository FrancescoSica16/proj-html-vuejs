<template>
  <header>
      
        <div id="pre-nav" class="col-10 d-flex justify-content-between">

          <div id="open-hours" class="">
            <p>Open Hours: Mon - Sat - 9:00-18:00</p>
          </div>

          <div id="contacts" class="d-flex">
            <div id="numbers" class="d-flex">
              <i class="fas fa-phone-alt"></i>
              <p>3318994486</p>
            </div>
            <div id="mail" class="d-flex"> 
              <i class="fas fa-envelope"></i>
              <p>hello@gmail.com</p>
            </div>
            <div id="social">
              <i class="fab fa-facebook-f"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-linkedin-in"></i>
            </div>
          </div>
        </div>
       
  </header>
</template>

<script>
export default {
  name: 'Header',
  props: [],

  data: function() {
    return{
      
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
@import "../style/general.scss";
@import "../style/variabiles.scss";
  
  #pre-nav{
    background-color: #1d2528;
    height: 40px;
  }

</style>
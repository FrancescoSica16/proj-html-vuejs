<template>
  <header>
    <div class="container">
      <div class="row">
        <div id="pre-nav" class="col-12 d-flex justify-content-between">

          <div id="open-hours" class="d-flex">
            <div>Open Hours: Mon-Sat - 9:00-18:00</div>
          </div>

          <div id="contacts" class="d-flex ">
            <div id="numbers" class="d-flex align-items-center ">
              <i class="fas fa-phone-alt"></i>
              <div>3318994486</div>
            </div>
            <div id="mail" class="d-flex align-items-center"> 
              <i class="fas fa-envelope"></i>
              <div>hello@gmail.com</div>
            </div>
            <div id="social" class="d-flex align-items-center">
              <i class="fab fa-facebook-f"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-linkedin-in"></i>
            </div>
          </div>
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
  
header{
  background-color: #1d2528;
  height: 40px;
}

#pre-nav{
  margin: 5px 0;
}

#pre-nav div, i{
  color: #bcbdbd;
  
}

#pre-nav i{
    padding-right: 10px;
}

#contacts div {
  padding-right: 15px;
}
</style>
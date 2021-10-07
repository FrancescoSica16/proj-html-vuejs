<template>
  <header>
    <div class="container-fluid">
      <div class="row">
        <div class="col-10 m-auto">
        <div id="pre-nav" class=" d-flex justify-content-between flex-nowrap">

          <div id="open-hours" class="d-flex text-nowrap">
            <div>Open Hours: Mon-Sat - 9:00-18:00</div>
          </div>

          <div id="contacts" class="d-flex flex-nowrap">
            <div id="numbers" class="d-flex align-items-center ">
              <i class="fas fa-phone-alt"></i>
              <div>3318994486</div>
            </div>
            <div id="mail" class="d-flex align-items-center"> 
              <i class="fas fa-envelope"></i>
              <div>hello@gmail.com</div>
            </div>
            <div id="social" class="d-flex align-items-center p-0">
              <i class="fab fa-facebook-f"></i>
              <i class="fab fa-twitter"></i>
              <i class="fab fa-linkedin-in p-0"></i>
            </div>
          </div>
        </div>
      </div>
      </div>     
    </div> 
    <div id="jumbotron" class="container-fluid">
      <div class="row">               
        <nav class="col-10 m-auto d-flex justify-content-between navbar navbar-expand-lg ">
          <img class="navbar-brand" href="#" src="..\assets\img\nexgen-logo.svg" alt="" > 

          <div class="navbar-nav m-0 d-flex align-items-center flex-nowrap">
            <a v-for="(navItem, index) in headerData" :key="index" class="nav-link" :href="navItem.link">{{navItem.name}}</a>           
            <span><i class="far fa-user" href="#contacts"></i></span>
            <button class="btn my_button_primary">GET IN TOUCH</button>        
          </div>    
        </nav>
        
      </div>
    </div>
   
  </header>
</template>

<script>
import headerData from "../data/headerData.js";
export default {
  name: 'Header',
  props: [],

  data: function() {
    return{
      headerData,
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
  
}

#pre-nav{
  margin: 5px 0;
}

#pre-nav div, i{
  color: #bcbdbd;
  margin: 0;
  
}

#pre-nav i{
    padding-right: 10px;
}

#contacts div {
  padding-right: 15px;
}

#jumbotron{
  background-image: url(../assets/img/bg-2.jpg);
  background-size: cover;
  height: 600px;
}
.navbar-brand{
  height: 50px;
}
.navbar-nav{

  .nav-link{
  text-transform: uppercase;
  color: $textNavFooter;
  font-weight: 600;
  }
  i{
    color: white;
    padding: 0 10px ;
  }
}
.nav-link{
  text-transform: uppercase;
  color: $textNavFooter;
  font-weight: 600;

}
</style>
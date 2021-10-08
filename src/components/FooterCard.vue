<template>     
    <li>
        <a :href="rif">{{title}}</a>
    </li>
</template>

<script>

export default {
  name: "FooterCard",
  props: ["title", "rif"],
  components:{
      
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

    a{
        text-decoration: none;
        color: $textNavFooter;
    }
    li{
        line-height: 2;
    }
    
     li:before{
        content: "\203A";
        color: $textNavFooter;       
        margin-right: 10px;
    }

</style>
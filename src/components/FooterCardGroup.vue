<template>
    <div class="container">
        <div class="row">
            <div class="col-10 m-auto d-flex justify-content-center  mt-5">
            
            <div class="card py-3">
                <h3>About</h3>
                <ul>
                    <FooterCard v-for="(aboutItem, index) in about" 
                    :key="index" :title="aboutItem.name" :rif="aboutItem.link"/>
                </ul>           
            </div>
            <div class="card py-3">
                <h3>Service</h3>
                <ul>
                    <FooterCard v-for="(serviceItem, index) in service" 
                    :key="index" :title="serviceItem.name" :rif="serviceItem.link"/>
                </ul>         
            </div>
               <div class="card py-3">
                   <h3>Support</h3>
                <ul>
                    <FooterCard v-for="(supportItem, index) in support" 
                    :key="index" :title="supportItem.name" :rif="supportItem.link"/>
                </ul>         
            </div>
            
            </div>
        </div>
    </div>
</template>

<script>
import FooterCard from "./FooterCard.vue";


export default {
  name: "FooterCardGroup",
  props: [],
  components:{
      FooterCard,
     
  },
  data: function() {
    return{
       
    about :[
        {
            name:"The Company",
            link:"#"
        },
        {
            name:"Istitutional",
            link:"#"
        },
        {
            name:"Social Event",
            link:"#"
        },
        {
            name:"Innovation",
            link:"#"
        },
        {
            name:"Enviroment",
            link:"#"
        },
        {
            name:"Technology",
            link:"#"
        }
    ],
    service:[
    {
        name:"Service1",
        link:"#"

    },
    {
        name:"Service2",
        link:"#"
    },
    {
        name:"Service3",
        link:"#"
    },
    {
        name:"Service4",
        link:"#"
    },
    {
        name:"Service5",
        link:"#"
    },
    {
        name:"Service6",
        link:"#"
    }
    ],
    support:[
    {
        name:"Support1",
        link:"#"
    },
    {
        name:"Support2",
        link:"#"
    },
    {
        name:"Support3",
        link:"#"
    },
    {
        name:"Support4",
        link:"#"
    },
    {
        name:"Support5",
        link:"#"
    },
    {
        name:"Support6",
        link:"#"
    }
    ]
    }
  }
}
</script>

<style scoped lang="scss">
@import "../style/general.scss";
@import "../style/variabiles.scss";

.card{
    width: calc(100% /4);
    background-color: #ffffff10;
    margin: 0 10px;

    & ul{
       list-style-type: none;
       padding: 0; 
       margin: auto;
    }

    & h3{
        text-align: center;
        color: $textNavFooter;
        margin-bottom: 20px;
    }
}
</style>
<script>
import Header from "./components/Header.vue";
import axios from "axios";

export default {

  components:{
    Header,
  },


  data() {
    return {
      title: "Hello world"
    }
  },

  methods:{

  },

  created(){
    console.log(axios);
  }


  


 
};
</script>

<template>

  <Header/>

 
</template>

<style lang="scss" scoped></style>
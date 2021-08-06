<template>
<!--  <Tutorial/>-->
  <div>
    <Header/>
    <p>{{title}}</p>
    <hello-world message='This is a message.'/>
  </div>
</template>

<script>
import HelloWorld from "~/components/HelloWorld";
import Header from "~/components/Header";
export default {
  data:function(){
    return{
      title:'Hello, World!!',
    }
  },
  components:{
    Header,
    HelloWorld
  }
}
</script>

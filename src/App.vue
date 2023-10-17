<template>
  <div class="text1">
    <div>
      <img src="./assets/logo.png" alt="">
    </div>
    <h1>Hello {{ name }} AGE: {{ age}}</h1>  
    <p v-html="msg"></p>
    <p v-pre>Eample: {{ name }} </p>
  </div>
</template>

<script>
 export default{
    data() {
      return {
         name: "Mark", 
         age: "45", 
         msg:"<storage>Hello Vue</storage>"
     };
   }
 }
</script>

<style>
 h1{
  color: blueviolet;
 }
 .text1{
    font-size: 30px;
 }
</style>

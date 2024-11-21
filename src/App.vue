<script setup>
import Circle from "./components/Circle.vue"

function startLight(){
  document.getElementById("firstL").style.display ="none";
}
</script>

<template>
  <div>
    <div id="firstL">
      <Circle style = "background-color: red"></Circle>
    </div>
    <div id="secondL">
      <Circle style = "background-color: yellow"></Circle>
    </div>
        <div id="lastL">
      <Circle style = "background-color: green"></Circle>
    </div>
    <button @click="startLight">Start</button>
  </div>
</template>

<style scoped>
  button{
    margin: 10px 0 0 0;
  }
</style>

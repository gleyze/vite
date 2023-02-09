<template>
  <img alt="Vue logo" src="./assets/logo.png" />
  <HelloWorld msg="Hello Vue 3 + Vite" />
</template>

<script setup>
import HelloWorld from './components/HelloWorld.vue'

// This starter template is using Vue 3 experimental <script setup> SFCs
// Check out https://github.com/vuejs/rfcs/blob/script-setup-2/active-rfcs/0000-script-setup.md
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}

.btn{
  padding: 5px;
  margin: 5px; 
  border: 5px solid pink;
  text-transform: uppercase;
  font-weight: bold;
  font-style: italic;
  text-decoration: underline;
}

.btn:hover{
  background-color: pink;
}

.btn:focus {
  background-color: hotpink; 
}

.all{
  border-style: dotted;
  border-width: 10px;
  border-color: pink;
  width: 500px;
  max-width: 600px;
  margin: auto;
  background-color: skyblue;
}

.title{
  text-align: center;
  font-size: 40px;
}

.header{
  text-align: center;
}
.paragraph{
   text-align: center;
}
img {
  width: 400px;
}

p {
  text-align: center; 
  font-size: 20px;
  padding: 15px;
  color: red;
}

.detailButton {
  padding: 5px;
  margin: 5px; 
  border: 5px solid pink;
  text-transform: uppercase;
  font-weight: bold;
  font-style: italic;
  text-decoration: underline; 
}

  @media (min-width: 500px) and (max-width: 800px) {
    
    .detailButton {
      display: none;
    }

@media (max-width: 500px) {
  .all{
    transform: scale(0.8);
  }
}

</style>

<template>
  <div class="flex items-center w-full h-screen m-0 bg-black">
    <div class="h-full items-center flex bg-cyan-400">
      <SideBar msg="Sidebar"/>
    </div>
    <div class=" w-full h-full flex items-center justify-center">
      <div class="">
        <p  id="" class="text-white font-bold text-left">DEVELOPER</p>
        <h1 id="" class="font-bold text-5xl text-left text-cyan-400">PORT<span class="text-white">FOLIO</span></h1>
        <p  id="" class="text-cyan-400 font-bold text-right">SHAQUR ADAIR</p>
      </div>                   
    </div>
  </div>
</template>

<script>
import SideBar from './components/SideBar.vue'


export default {
  name: 'App',
  components: {
    SideBar,
    
}
}
</script>

<style>
#app {
  font-family: times;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  background-color: black;
}
</style>

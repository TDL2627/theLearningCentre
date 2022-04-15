<script setup>
import Landing from './components/Landing.vue'
import About from './components/About.vue'
import Gallery from './components/Gallery.vue';
import Team from './components/Team.vue';

</script>

<template>
<Landing/>
<About/>
<Gallery/>
<Team/>
</template>

<style>
#app{
  background: white;
  padding: 0 !important;
  margin: 0 !important;
}
body{
  margin:0;
  padding: 0;
  width: 100%;
}
</style>

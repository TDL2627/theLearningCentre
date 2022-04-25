<script setup>
import Landing from './components/Landing.vue'
import About from './components/About.vue'
import Gallery from './components/Gallery.vue';
import Team from './components/Team.vue';
import Testimonials from './components/Testimonials.vue';
import Contact from './components/Contact.vue';
import Footer from './components/Footer.vue';
import Apply from './components/Apply.vue';
import Home from './components/Home.vue';


</script>

<template>
<Home/>
<About/>
<Gallery/>
<Team/>
<Testimonials/>
<Apply/>
<Contact/>
<Footer/>
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
  .mainhead{
    padding-top: 50px;
    padding-bottom: 20px;
  } 
  /* width */
::-webkit-scrollbar {
  width: 15px;
}

/* Track */
::-webkit-scrollbar-track {
  background: palevioletred;
}

/* Handle */
::-webkit-scrollbar-thumb {
  background: yellow;
    border-radius: 25px;

}

/* Handle on hover */
::-webkit-scrollbar-thumb:hover {
  background: blue;
}

</style>

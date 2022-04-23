<template>
  <div id="home">


 <div class="relative overflow-hidden">
    <div class="max-w-7xl mx-auto text-center">
<nav id="nav2">
 <a href="#about" class="linky1 font-medium text-yellow-500 hover:text-gray-700">About</a>
  
                <a href="#gallery" class="linky2 font-medium text-pink-700 hover:text-gray-700">Gallery</a>

                <a href="#team" class="linky1 font-medium text-yellow-500  hover:text-gray-700">Team</a>

               <a href="#testimonials" class="linky2 font-medium text-pink-700 hover:text-gray-700">Testimonials</a>
                      <a href="#rules" class="linky1 font-medium text-yellow-500 hover:text-gray-700">Rules</a>

                <a href="#contact" class="linky2 font-medium text-pink-700 hover:text-gray-700">Contact</a>
</nav>

<div class="sm:text-center lg:text-left">
    <div class="intro">
   <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">
              <span class="block inline text-pink-500 ">T</span><span style="color:white;" class="block  inline animate__animated animate__fadeInDown animate__slow animate__delay-1s">HE</span> <br>
              <span class="block text-yellow-500 inline">L</span><span style="color:white;" class="block inline animate__animated animate__fadeInDown animate__slow animate__delay-2s">EARNING</span><br>
              <span class="block text-blue-500 inline">C</span><span style="color:white;" class="block inline animate__animated animate__fadeInDown animate__slow animate__delay-3s">ENTRE</span><br>
            </h1>
    </div>
         
            <br>
             <span class="block text-black inline">ADAPTED LEARNING SPECIALIST</span>
             <br><br>

            <p class="mt-3 text-base text-gray-700 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
              <span class="block inline text-pink-500">VISION : </span><span class="block  inline">Inclusive learning for all.</span> <br>
              <span class="block inline text-blue-500">MISSION : </span><span class="block  inline">If I don't learn the way you teach then teach the way I learn.</span> <br>
              </p>
          </div>

    </div>
 </div>
  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
#home{
    height: 100vh;
      background:linear-gradient(0deg, rgba(0, 0, 0, 0.8), rgba(0, 0, 0, 0.8)), url("../assets/kiddo.jpg");

}
#nav2{
    position: fixed;
    top: 0;
    left:0;
    width: 100%;
    z-index: 123456789;
}
.intro{
    margin-left: 40%;
    margin-top: 10%;
}
</style>
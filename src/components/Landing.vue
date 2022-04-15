<template>
<div id="landing">

<div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto">
      <div class="relative z-10 pb-8 bg-white sm:pb-16 md:pb-20 lg:max-w-2xl lg:w-full lg:pb-28 xl:pb-32">
        <svg class="hidden lg:block absolute right-0 inset-y-0 h-full w-48 text-white transform  translate-x-1/2" fill="currentColor" viewBox="0 0 100 100" preserveAspectRatio="none" aria-hidden="true">
          <polygon points="50,0 100,0 50,100 0,100" />
        </svg>
  
        <div>
          <div class="relative pt-6 px-4 sm:px-6 lg:px-8 navie">
            <nav class="relative flex items-center justify-between sm:h-10  lg:justify-start" aria-label="Global">
              <div class="flex items-center flex-grow flex-shrink-0 lg:flex-grow-0">
                <div class="flex items-center justify-between w-full md:w-auto">
                  <a href="#">
                    <img class="h-8 w-auto sm:h-10 navpic" src="../assets/hand.png" alt="logo">
                    </a>

                    <button class="btn buttie float-end" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasExample" aria-controls="offcanvasExample">
 <img src="../assets/hamburger.png" alt="">
</button>
                              
                </div>
              </div>
              <div class="hidden md:block md:ml-10 md:pr-4 md:space-x-8">
                <a href="#" class="linky1 font-medium text-yellow-500 hover:text-gray-700">About</a>
  
                <a href="#" class="linky2 font-medium text-pink-700 hover:text-gray-700">Gallery</a>

               <a href="#" class="linky1 font-medium text-yellow-500 hover:text-gray-700">Testimonials</a>

  
                <a href="#" class="linky2 font-medium text-pink-700 hover:text-gray-700">Team</a>
  
                <a href="#" class="linky1 font-medium text-yellow-500 hover:text-gray-700">Contact</a>
  
              </div>
            </nav>
          </div>
  
       
       
        </div>
  
        <main class="mt-10 mx-auto max-w-7xl px-4 sm:mt-12 sm:px-6 md:mt-16 lg:mt-20 lg:px-8 xl:mt-28">
          <div class="sm:text-center lg:text-left">
            <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">
              <span class="block inline text-pink-500">T</span><span class="block  inline">HE</span> <br>
              <span class="block text-yellow-500 inline">L</span><span class="block inline">EARNING</span><br>
              <span class="block text-blue-500 inline">C</span><span class="block inline">ENTRE</span><br>
            </h1>
            <br>
             <span class="block text-black inline">ADAPTED LEARNING SPECIALIST</span>
             <br><br>

            <p class="mt-3 text-base text-gray-700 sm:mt-5 sm:text-lg sm:max-w-xl sm:mx-auto md:mt-5 md:text-xl lg:mx-0">
              <span class="block inline text-pink-500">VISION : </span><span class="block  inline">Inclusive learning for all.</span> <br>
              <span class="block inline text-blue-500">MISSION : </span><span class="block  inline">If I don't learn the way you teach then teach the way I learn.</span> <br>
              </p>
          </div>
        </main>
      </div>
    </div>
    <div class="lg:absolute lg:inset-y-0 lg:right-0 lg:w-1/2">
      <img class="h-56 w-full object-cover sm:h-72 md:h-96 lg:w-full lg:h-full" src="../assets/kiddo.jpg" alt="">
    </div>
  </div>
<!-- off canvas -->
<div class="offcanvas offcanvas-start" tabindex="-1" id="offcanvasExample" aria-labelledby="offcanvasExampleLabel">
  <div class="offcanvas-header">
    <h5 class="offcanvas-title" id="offcanvasExampleLabel">Offcanvas</h5>
    <button type="button" class="btn-close text-reset" data-bs-dismiss="offcanvas" aria-label="Close"></button>
  </div>
  <div class="offcanvas-body">
    <div>
      Some text as placeholder. In real life you can have the elements you have chosen. Like, text, images, lists, etc.
    </div>
    <div class="dropdown mt-3">
      <button class="btn btn-secondary dropdown-toggle" type="button" id="dropdownMenuButton" data-bs-toggle="dropdown">
        Dropdown button
      </button>
      <ul class="dropdown-menu" aria-labelledby="dropdownMenuButton">
        <li><a class="dropdown-item" href="#">Action</a></li>
        <li><a class="dropdown-item" href="#">Another action</a></li>
        <li><a class="dropdown-item" href="#">Something else here</a></li>
      </ul>
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
.buttie{
  display: none;
}
  a{
    border-radius: 25px;
    text-decoration: none;
  }
  .linky1{
border: 2px solid yellow;
padding: 10px;
  }
  .linky2{
    padding: 10px;
border: 2px solid pink;
  }
  .linky1:hover{
    background: yellow;
  }
  .linky2:hover{
    background: pink;
  }
@media only screen and (max-width:700px) {
  .navie{
    background-color:black;
    padding-top: 10px;
    padding-bottom: 10px;
  }
  .buttie{
    display: initial;
  }


}

</style>
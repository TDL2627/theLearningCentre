<template>
  <div id="gallery">
<div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto text-center">
   <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl mainhead">GALLERY</h1>
   <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active c1">
      <img src="../assets/gallery/one1.jpg" class="d-block w-100" alt="kidz">
    <h3>One on one learning</h3>
    </div>
    <div class="carousel-item c1">
      <img src="../assets/gallery/one2.jpg" class="d-block w-100" alt="kidz">
         <h3>One on one learning</h3>
    </div>
    <div class="carousel-item c1">
      <img src="../assets/gallery/one3.jpg" class="d-block w-100" alt="kidz">
         <h3>One on one learning</h3>
    </div>
      <div class="carousel-item c1">
      <img src="../assets/gallery/one4.jpg" class="d-block w-100" alt="kidz">
         <h3>One on one learning</h3>
    </div>
  <div class="carousel-item c2">
      <img src="../assets/gallery/therapy1.jpg" class="d-block w-100" alt="kidz">
         <h3>Sensory Therapy</h3>
    </div>
      <div class="carousel-item c2">
      <img src="../assets/gallery/therapy2.jpg" class="d-block w-100" alt="kidz">
         <h3>Sensory Therapy</h3>
    </div>
      <div class="carousel-item c2">
      <img src="../assets/gallery/therapy3.jpg" class="d-block w-100" alt="kidz">
         <h3>Occupational Therapy</h3>
    </div>
  <div class="carousel-item c2">
      <img src="../assets/gallery/therapy4.jpg" class="d-block w-100" alt="kidz">
         <h3>Speech Therapy</h3>
    </div>
  <div class="carousel-item c1">
      <img src="../assets/gallery/env1.jpg" class="d-block w-100" alt="kidz">
         <h3>Premises</h3>
    </div>
  <div class="carousel-item c1">
      <img src="../assets/gallery/env2.jpg" class="d-block w-100" alt="kidz">
         <h3>Premises</h3>
    </div>
  <div class="carousel-item c1">
      <img src="../assets/gallery/env3.jpg" class="d-block w-100" alt="kidz">
         <h3>Premises</h3>
    </div>

      <div class="carousel-item c2">
      <img src="../assets/gallery/out1.jpg" class="d-block w-100" alt="kidz">
         <h3>Outings and events</h3>
    </div>

      <div class="carousel-item c2">
      <img src="../assets/gallery/out2.jpg" class="d-block w-100" alt="kidz">
         <h3>Outings and events</h3>
    </div>

    
      <div class="carousel-item c2">
      <img src="../assets/gallery/out3.jpg" class="d-block w-100" alt="kidz">
         <h3>Outings and events</h3>
    </div>

   <div class="carousel-item c1">
      <img src="../assets/gallery/Pec.jpg" class="d-block w-100" alt="kidz">
         <h3>Pecs</h3>
    </div>

       <div class="carousel-item c2">
      <img src="../assets/gallery/talk.jpg" class="d-block w-100" alt="kidz">
         <h3>Talking App</h3>
    </div>


  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Previous</span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleControls" data-bs-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="visually-hidden">Next</span>
  </button>
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
.carousel{
    border-radius: 25px;
    margin: 5%;
}
.c1{
   border: 10px pink solid;
    background: pink;
}
.c2{
    border: 10px rgb(64, 64, 253) solid;
    background: rgb(64, 64, 253);
    color: white;
}
img{
    height: 70vh;
     border-radius: 20px;
    object-fit: cover;
}
.carousel-control-prev-icon, .carousel-control-next-icon{
  background-color: blue !important;
  border-radius: 50%;
  padding: 30px;
}

</style>
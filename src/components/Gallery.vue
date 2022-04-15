<template>
  <div id="gallery">
<div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto text-center">
   <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">GALLERY</h1>
   <div id="carouselExampleControls" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="../assets/kids1.jpg" class="d-block w-100" alt="kidz">
    </div>
    <div class="carousel-item">
      <img src="../assets/kids2.jpg" class="d-block w-100" alt="kidz">
    </div>
    <div class="carousel-item">
      <img src="../assets/kids3.jpg" class="d-block w-100" alt="kidz">
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
    border: 10px yellow solid;
    border-radius: 25px;
    margin: 5%;
}
img{
    height: 70vh;
    object-fit: cover;
}
.carousel-control-prev-icon, .carousel-control-next-icon{
  background-color: blue !important;
  border-radius: 50%;
  padding: 30px;
}

</style>
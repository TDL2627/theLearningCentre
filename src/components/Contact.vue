<template>
    <div id="contact">
 <div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto text-center">
   <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl mainhead">CONTACT</h1>

<div class="container">
<div class="row">
    <div class="col-lg-6">
        <h5>Address : </h5>
              <p>40 Bongo Crescent,Silvertown, Athlone, Cape Town, 7764, South Africa</p>
              <h5>Phone :</h5>
              <p>+27749594511</p>
              <h5>What's App :</h5>
              <a  target="_blank" href="https://wa.me/27749594511"><img id="wapp" src="https://img.icons8.com/external-justicon-flat-justicon/64/000000/external-whatsapp-social-media-justicon-flat-justicon.png"/></a>
              <h5>Email :</h5>
              <p>safodienfazlin07@gmail.com</p>
    </div>
<div class="col-lg-6">
<form  action="https://formspree.io/f/xgednpkq"
  method="POST" target="_blank">
    <div class="mb-3">
    <label for="exampleInputName1" class="form-label">Full Name</label>
    <input name="name" type="text" class="form-control" id="exampleInputName1" >
    <div  class="form-text"></div>
  </div>
  <div class="mb-3">
    <label for="exampleInputEmail1" class="form-label">Email address</label>
    <input type="email" name="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
    <div  class="form-text">We'll never share your email with anyone else.</div>
  </div>
  <div class="mb-3">
    <label class="form-label">Cell phone number</label>
    <input type="number" name="number" class="form-control" >
  </div>

  <button type="submit" class="btn btn-primary">Submit</button>
</form>

</div>

</div>

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
form{
    background: rgba( 253, 216, 0, 0.4 );
box-shadow: 0 8px 32px 0 rgba( 31, 38, 135, 0.37 );
backdrop-filter: blur( 4px );
-webkit-backdrop-filter: blur( 4px );
border-radius: 10px;
border: 1px solid rgba( 255, 255, 255, 0.18 );
padding:10px;
margin-bottom: 50px;
}
#wapp{
    margin-left: 42%;
}
</style>
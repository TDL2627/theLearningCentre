<template>
    <div id="contact">
 <div class="relative bg-white overflow-hidden">
    <div class="max-w-7xl mx-auto text-center">
   <h1 class="text-4xl tracking-tight font-extrabold text-gray-900 sm:text-5xl md:text-6xl">CONTACT</h1>
<form
  action="https://formspree.io/f/xrgjyywq"
  method="POST"
>
  <label>
    Your name:
    <input type="name" name="name">
  </label>
  <label>
    Your email:
    <input type="email" name="email">
  </label>
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <button type="submit">Send</button>
</form>
    </div>
 </div>

  </div>
</template>

<script>
export default {

}
</script>

<style scoped>
@media only screen and (max-width:700px) {
   #contact{
    padding-top: 50px;
  } 
}
</style>
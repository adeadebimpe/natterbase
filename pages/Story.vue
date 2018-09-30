<template>
  <div class="about-template">
      <secondNavbar />
    <div class="page-header">
      <div class="container">
        <h1 class="text-center">Customer Story</h1>
        <h4 class="text-center text-whiet">Stories from the horse’s mouth</h4>
      </div>
    </div>
    <section class="convinced">
      <div class="container d-flex flex-column align-items-center">
        <h4 class="text-center"> Still not convinced?</h4>
        <p class="text-center">We’ve done some amazing work for clients that have become
like family. Now, they can’t stop chanting our name and singing our high praises. Read them yourself and see that truly the reputation of our services is primo.</p>
      </div>
    </section>
   
  </div>
</template>
<script>
  import secondNavbar from '../components/secondNavbar'
 
  export default {
    components: {
      secondNavbar
    }
  }
</script>
<style>
    
    .convinced {
        margin-bottom: 100px;
    }
   
    .convinced p{
        font-size: 20px;
        max-width: 521px;
    }
    .bg-grey{
        background-color: #f7f7f7;
    }
</style>

<template>
  <div class="about-template">
      <secondNavbar />
    <div class="page-header">
      <div class="container">
        <h1 class="text-center">Case Study</h1>
        
      </div>
    </div>
    <section class="convinced">
      <div class="container d-flex flex-column align-items-center">
        <h4 class="convinced-text"> At Natterbase, we have got all the right guns to make your project experience successful and we are not afraid to use it. </h4>
        <p class="convinced-text">Once you’ve been connected to the developer of your choice from different part of the world to work on your project, you pay based on the number of hours worked. your charge is also determined by the speed and accuracy of the developer.</p>
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
    .convinced-text{
        max-width: 700px;
    }
    .page-header{
        background-color: #000;
        padding: 200px 0px;
        color: #fff;
        margin-bottom: 100px;

    }
    .page-header h1{
        font-weight: 200;
        font-size: 65px;	
        line-height: 73px;
    }
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

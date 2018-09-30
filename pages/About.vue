<template>
  <div class="about-template">
      <secondNavbar />
    <div class="page-header">
      <div class="container">
        <h1 class="text-center">About Zeedas</h1>
      </div>
    </div>
    <section class="project-management">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <h4>Project management tool that seamlessly track the progress of a project in real-time.</h4>
          </div>
          <div class="col-md-6">
            <p>Zeedas is a premium-satisfaction project management tool that seamlessly track the progress of a project
              in real-time.
              This executive tool has several ways to which it can be used to manage project such and ease project
              development
              for both the client and the developer.</p>
          </div>
        </div>
      </div>
    </section>
    <section class="how-it-works bg-grey">
      <div class="container">
        <h2 class="mb-5 text-center">How it works for the developer</h2>
        <div class="row align-items-center">
          <div class="col-md-6">
            <h4 class="mb-4">
              Code reusability
            </h4>
            <p class="mb-4">
              ​Zeedas allows for developers to recycle existing codes for new projects thereby saving time and money.
              After creating a task, Zeedas automatically identifies bits of code that already exist in your repository
              and recycle them; thereby saving costs and time that could be used to write a new line of codes.
            </p>
          </div>
          <div class="col-md-6">
              <img src="~/assets/images/About Zeedas/Code Usability.svg" alt="Code Usability" width="100%">
          </div>
        </div>
      </div>
    </section>
    <section class="how-it-works ">
      <div class="container">

        <div class="row align-items-center">

          <div class="col-md-6">
               <img src="~/assets/images/About Zeedas/Decentralized Product.svg" alt="Decentralized Product" width="100%">
          </div>
          <div class="col-md-6">
            <h4 class="mb-4">
              Decentralized product deployment​
            </h4>
            <p class="mb-4">
              ​Zeedas allows you to break your project into smaller
              clods and assign them to different developers around the world. Each developer work on their task
              independently so when they deploy, their code is seamlessly put together.
            </p>
          </div>
        </div>
      </div>
    </section>
    <section class="how-it-works  bg-grey">
      <div class="container">
        <h2 class="mb-5 text-center">How it works for the developer</h2>
        <div class="row align-items-center">
          <div class="col-md-6">
            <h4 class="mb-4">
              Developer Analysis
            </h4>
            <p class="mb-4">
              ​Zeedas shows you a developers working hours and workrate by integrating with the developers working
              environment.
              It grants an all in-one accessibilities, that tracks the speed of each developers which would help you
              monitor the time a developer
              spends on his project and how fast the said developer is in completing his project from anywhere in the
              world.
            </p>
          </div>
          <div class="col-md-6">
              <img src="~/assets/images/About Zeedas/Developer Analysis.svg" alt="Developer Analysis" width="100%">
          </div>
        </div>
      </div>
    </section>
    <section class="how-it-works">
      <div class="container">

        <div class="row align-items-center">

          <div class="col-md-6">
               <img src="~/assets/images/About Zeedas/IP Protection.svg" alt="IP Protection" width="100%">
          </div>
          <div class="col-md-6">
            <h4 class="mb-4">
              IP Protection
            </h4>
            <p class="mb-4">
              ​​It is equipped with an IP control module that guarantees the safety of you source code. This ensures that developers have access to only modules assigned to them, protecting the full source code.
            </p>
          </div>
        </div>
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
    
    .how-it-works{
        padding: 150px 200px;
       
    }
    @media only screen and (max-width: 768px){
      .how-it-works{
        padding: 100px 50px;
       
    }
    }
    .project-management{
        padding: 150px 0px;
    }
    
    .bg-grey{
        background-color: #f7f7f7;
    }
</style>

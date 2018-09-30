<template>
  <div class="about-template">
    <secondNavbar />
    <div class="page-header">
      <div class="container">
        <h1 class="text-center">Developer Story</h1> 
      </div>
    </div>
    <section class="convinced">
      <div class="container">
        <div class="row">
            <div class="col-md-6">
              <h2 class="mb-5">Team member stories</h2>
              <p>Here is what a few of our outstanding developers have to say about their work, 
                processes and experience working with a detail-oriented product company like Natterbase
                 to meet diverse objectives.
              </p>
            </div>
            <div class="col-md-6">
              <h6>Insider story</h6>
            </div>
        </div>
        <div class="row d-flex align-items-center">
            <div class="col-md-6">
              
            </div>
            <div class="col-md-6">
             <h4 class="mb-5">At Natterbase, we have got all the right guns to make your project experience successful and we are not afraid to use it. </h4>

             <p>Our fluid means of execution enables visibility on the side of the client as they can choose the developers
                they desire based on the skill set that best aligns with their project requirements and most importantly, speed and accuracy on our side. </p> 

                <p>You can monitor the speed and accuracy of developers, assign tasks to them and monitor the progress of your project. 
                  Even better, all your code remains secure and access can be restricted as required. </p>
            </div>
        </div>
      </div>
    </section>
    <section class="dark">
    
    </section>
    <section class="map my-5">
      <div class="container">
         <img src="~/assets/images/Home/Map - Dotted World Map.svg" alt="Map" width="100%">
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
    }
    .bg-grey{
        background-color: #f7f7f7;
    }
    .dark{
      background-color: #000;
      height: 500px;
    }
</style>

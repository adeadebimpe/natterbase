<template>
  <div class="about-template">
    <secondNavbar />
    <div class="page-header">
      <div class="container">
        <h1 class="text-center">Our Rates</h1>

      </div>
    </div>
    <section class="convinced">
      <div class="container d-flex flex-column align-items-center">

        <p class="text-center">As you know, we pride ourselves on the simplicity, accuracy and speed of our project
          execution methodology; hence, we have also made our costing process a walk in the park for our
          esteemed clients.</p>
      </div>
    </section>
    <section class="rates-text my-5">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <h4 class="my-5">At Natterbase, we have got all the right guns to make your project experience successful
              and we are not afraid to use it. </h4>
            <p>Once you’ve been connected to the developer of your choice from different part of the world to work on
              your project, you pay based on the number of hours worked. your charge is also determined by the speed
              and accuracy of the developer.</p>
          </div>
        </div>
      </div>
    </section>
    <section class="first-card">
      <div class="container">
        <h2 class="text-center">
          Hire a developer in 3 simple steps
        </h2>
        <div class="row my-5 align-items-center">
          <div class="col-md-4 d-flex">
            <h1 class="faded-number">1</h1>
            <p class="top-text">Developer <br> Working Hours</p>
          </div>
          <div class="col-md-8">
            <div class="row">
              <div class="col-md-4">
                <div class="ratecard">
                  <p class="text-center">Onsite</p>
                </div>
              </div>
              <div class="col-md-4">
                <div class="ratecard">
                  <p class="text-center">Remote</p>
                </div>
              </div>
            </div>


          </div>
        </div>
        <div class="row my-5 align-items-center">
          <div class="col-md-4 d-flex">
            <h1 class="faded-number">2</h1>
            <p class="top-text">Estimated working <br> hours for Developers</p>
          </div>
          <div class="col-md-8">
            <div class="form-group">

              <input type="text" class="form-control" name="" id="" aria-describedby="helpId" placeholder="Enter your work duration ( E.g 5 hours )">

            </div>
          </div>


        </div>
        <div class="row my-5 align-items-center">
          <div class="col-md-4 d-flex">
            <h1 class="faded-number">3</h1>
            <p class="top-text">Slide to preferred<br> Developer Efficiency</p>
          </div>
          <div class="col-md-8">
            <div class="form-group">

              <input type="range" class="form-control" name="" id="" aria-describedby="helpId" placeholder="Enter your work duration ( E.g 5 hours )">
              <div class="row range unit">
                <div class="col-md-4">
                  <p>Beginner</p>
                </div>
                <div class="col-md-4">
                  <p class="text-center">Intermediate</p>
                </div>
                <div class="col-md-4">
                  <p class="text-right">World Class</p>
                </div>
              </div>
            </div>
          </div>


        </div>
        <div class="row my-5 py-5">
          <div class="col-md-4">
            <h1 class="faded-number">Total</h1>
          </div>
          <div class="col-md-4">
            <h1 class="text-center">N640k</h1>
            <p class="text-center">Monthly - Onsite</p>
          </div>
          <div class="col-md-4">
            <a href="#" class="btn btn-white">Hire Now</a>
          </div>
        </div>
      </div>

    </section>
    <section class="second-card">
      <div class="container">
        <h2 class="text-center">
          Outsource a project
        </h2>
        <div class="row my-5 align-items-center">
          <div class="col-md-4 d-flex">
            <h1 class="faded-number">1</h1>
            <p class="top-text">What is the device<br> for this project</p>
          </div>
          <div class="col-md-8">
            <div class="row">
              <div class="col-md-4">
                <div class="project-type">
                  <p class="text-center">Desktop</p>
                </div>
              </div>
              <div class="col-md-4">
                <div class="project-type">
                  <p class="text-center">Mobile</p>
                </div>
              </div>
              <div class="col-md-4">
                <div class="project-type">
                  <p class="text-center">Other</p>
                </div>
              </div>
            </div>


          </div>
        </div>
        <div class="row my-5 align-items-center">
          <div class="col-md-4 d-flex">
            <h1 class="faded-number">2</h1>
            <p class="top-text">What is the device<br> for this project</p>
          </div>
          <div class="col-md-8">
            <div class="row">
              <div class="col-md-4 ">
                <div class="project-type">
                  <p class="text-center">Front-End</p>
                </div>

              </div>
              <div class="col-md-4">
                <div class="project-type">
                  <p class="text-center">Back-End</p>
                </div>
              </div>
              <div class="col-md-4">
                <div class="project-type">
                  <p class="text-center">Design</p>
                </div>
              </div>
            </div>
          </div>


        </div>
        <div class="row my-5 align-items-center">
          <div class="col-md-4 d-flex">
            <h1 class="faded-number">3</h1>
            <p class="top-text">Enter your project<br>description</p>
          </div>
          <div class="col-md-8">
            <form action="">
              <div class="form-group">

                <textarea class="form-control" name="" id="" rows="8" placeholder="Type project description"></textarea>
              </div>
            </form>
            <a href="#" class="btn mt-5">Request a Quote</a>
          </div>


        </div>

      </div>

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

  .convinced p {
    font-size: 20px;
    max-width: 521px;
  }

  .bg-grey {
    background-color: #f7f7f7;
  }

  .first-card {
    background-color: #000;
    padding: 100px 0px;
  }

  .second-card {
    padding: 100px 0px;
  }

  .faded-number {
    font-size: 160px;
    color: #eaeaea;
    opacity: 0.2;
    font-weight: 600;
    position: relative;
  }

  .ratecard {
    padding: 100px 30px 30px 30px;
    background-color: #FFFFFF;
  }

  .top-text {
    position: absolute;
    top: 0px;
    left: 50px;
    color: #fff;
  }

  .second-card .faded-number {
    opacity: 1;
  }

  .top-text {
  color: #000;
  }
  .second-card h2{
    color: #fff;
  }
  .second-card textarea {
    border-radius: 0px;
    border: 1px solid #C8C8C8;
  }

  .project-type {
    background-color: #FFFFFF;
    box-shadow: 0 20px 20px 0 rgba(137, 137, 137, 0.19);
    padding: 100px 30px 30px 30px;
  }
  .project-type:hover{
      background-color: #000;
      color: #ffffff;
  }

</style>

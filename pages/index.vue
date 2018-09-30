<template>
  <div class="home-template">
    <Navbar />
    <div class="hero-header">
      <div class="container">
        <div class="row">
          <div class="col-md-1">

          </div>
          <div class="col-md-5">
            <h1>We drip with <br> creativity</h1>
          </div>
          <div class="col-md-6">
            <h5 class="sub-text">We are open-minded creative and our actions are influenced by the cognitive process which allows us to
              be the builders and problem solvers you seek.</h5>
          </div>
        </div>
        <div class="hero-header-bottom">
          <div class="row justify-content-start mt-5">
            <div class="col-md-1">
              <div class="scroll d-flex flex-column align-items-start justify-content-center">
                <p class="text-center">Scroll</p>
                <div class="scroll-down" v-scroll-to="'#about'"></div>
              </div>

            </div>
            <div class="col-md-11">
              <div class="video">
                <div class="container">
                  <div class="video-wrapper">
                    <video src="//clips.vorwaerts-gmbh.de/VfE_html5.mp4" poster="//s3-us-west-2.amazonaws.com/s.cdpn.io/3174/poster.png"></video>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>

      </div>
    </div>
    <section id="about" >
      <div class="container-fluid d-flex flex-column align-items-center">
        <h2 class="text-center mb-5">We have the best developers in Africa</h2>
      <p class="about-text text-center mb-5">Dive into our pool of world class software engineers who work remotely to
        keep your projects going and delivered in record time. All you have to do is pick one!</p>
      <a href="#" class="btn">Fish for a developer</a>
      </div>
    </section>
    <section id="known-for">
      <div class="container-fluid d-flex flex-column align-items-center">
        <h2 class="text-center mb-5">What are we known for</h2>
      <p class="about-text text-center mb-5">We are a global engineering platform that delivers premium product
        development in record time. We provide the world’s most mission-driven, goal-oriented engineering team to
        clients building visionary products.</p>
      </div>

    </section>
    <section class="features">
      <div class="container-fluid">
        <div class="row">
        <div class="col-md-6">
          <img src="~/assets/images/Home/Illustration - Hire.svg" alt="Illustration Hire" class="mb-2 img-fluid" width="100%">
        </div>
        <div class="col-md-6">
          <div class="row features-item">
            <div class="col-md-2 icon-top">
              <img src="~/assets/images/Home/Hire a developer.svg" alt="Hire a dev" class="mb-2 img-fluid" >
            </div>
            <div class="col-md-8">
              <h4 class="mb-4">
                Hire a developer
              </h4>
              <p class="about-text mb-4">
                Look through our community of skilled developers and hire one that matches the criteria for your
                project. Analysis on each developer is done which makes it easier for you to pick a developer based on
                speed, skill and accuracy.
              </p>
              <a href="#" class="btn">Hire Now</a>
            </div>
          </div>
          <div class="row features-item">
            <div class="col-md-2  icon-top">
              <img src="~/assets/images/Home/Outsource Project.svg" alt="Outsource" class="mb-2 img-fluid" >
            </div>
            <div class="col-md-8">
              <h4 class="mb-4">
                Outsource a project
              </h4>
              <p class="about-text mb-4">
                Outsource your project to our team of talented developers and be rest assured that it would be executed
                with precise focus, accuracy and delivered in record time.
              </p>
              <a href="#" class="btn">Outsource project</a>
            </div>
          </div>
        </div>
      </div>
      </div>
    </section>
    <section id="special">
      <div class="container">
        <div class="row">
          <div class="col-md-4">
            <h2 class="mb-4">What makes us <br> special</h2>
            <p class="text-white">With strog dedication and passion, our team can help you with the following services.</p>
          </div>
          <div class="col-md-8">
            <div class="row">
              <div class="col-md-6 mb-5">
                <img src="~/assets/images/Home/IP-Protection.svg" alt="IP Protection" class="mb-2">
                <h4 class="mb-4">
                  IP Protection
                </h4>
                <p class="mb-4">
                  
                  We provide you with the best tools that enable you track developer speed and accuracy and also manage
                  your project record in real time.
                  Our engineers are bright, fine and trusted in all of Africa.
                </p>
              </div>
              <div class="col-md-6 mb-5">
                <img src="~/assets/images/Home/Forecasting.svg" alt="Forecasting" class="mb-2">
                <h4 class="mb-4">
                  
                  Forecasting
                </h4>
                <p class="mb-4">
                  We use UX research to investigate and identify the consumer’s behavior across our target audiences,
                  acknowledge their goals, needs and overall modules. We put into consideration our target.
                </p>
              </div>
              <div class="col-md-6 mb-5">
                 <img src="~/assets/images/Home/In app Payment.svg" alt="In app payment" class="mb-2">
                <h4 class="mb-4">
                 
                  In app payment
                </h4>
                <p class="mb-4">
                  We’ve created a community of engineers who possess skill and experience in the fields of software
                  design,
                  software development, user experience, and interface design.
                </p>
              </div>
              <div class="col-md-6 mb-5">
                 <img src="~/assets/images/Home/Visibility.svg" alt="Visibility" class="mb-2">
                <h4 class="mb-4">
                  Visibility
                </h4>
                <p class="mb-4">
                  Natterbase enables decentralized outsourcing, reducing product development cost and timelines up to
                  60%.
                </p>
              </div>

            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="work">
      <div class="container">
        <h2 class="mb-5">Who we have worked with</h2>
        <div class="row">
          <div class="col-md-6">

            <h4 class="mb-4">
              We’ve provided optimal services to many top companies over time and they were impressed with
              how we executed and delivered their projects.
            </h4>
          </div>
          <div class="col-md-6">
            <p>We believe in technology as a vital tool for solving problems. Businesses around the world invest
              significant resources towards recruiting and retaining the best talent to harness this tool. We bring you
              the cream of the talent pool, available on your terms.</p>
          </div>
        </div>
      </div>
    </section>
     <section id="portfolio">
      <div class="container">
        <div class="row">
          <div class="col-md-6">


          </div>
          <div class="col-md-6">
             <h2 class="mb-5">Our Portfolio</h2>
            <p class="mb-5">See the companies that gave us a try. These companies tested waters with us and they loved it.</p>
             <a href="#" class="btn">Portfolio</a>
          </div>
        </div>
      </div>
    </section>
    <section id="testimonials">
      <div class="container">
        <h2 class="text-center ">What our clients say</h2>
        <div class="row mt-5">
          <div class="col-md-6">
           
          </div>
          <div class="col-md-6">
            <img src="~/assets/images/Home/Qoute.svg" alt="IP Protection" class="mb-4">
            <h2 class="mb-5">
              It took a lot less time than I anticipated for Natterbase to roll out my product. The level of professionalism was exactly as advertised.”
            </h2>
            <p class="name">Abolore Salami</p>
            <p class="job-description">Chief Executive Officer, Riby</p>
          </div>
        </div>
      </div>
    </section>
    <section id="best-dev">
      <div class="container">
        <div class="row">
          <div class="col-md-6">
            <img src="~/assets/images/Home/Illustration - Enjoy Process.svg" alt="Enjoy the dev process" width="100%">
          </div>
          <div class="col-md-6">
            <h2 class="mb-5">Enjoy the best <br> development process</h2>
            <h4 class="mb-4">99% more efficient</h4>
            <p class="mb-5">Natterbase shows you developers working hours, Speed and accuracy and work-rate by integrating with the developers working environment.</p>
            <a href="#" class="btn">Start a Project</a>
          </div>
        </div>
      </div>
    </section>
    <section id="remote">
      <div class="container">
        <div class="row">
          
          <div class="col-md-6">
            <h2 class="mb-5">Remote is the future</h2>
            <h4 class="mb-4">Code Reusability​</h4>
            <p class="mb-5">Natterbase shows you developers working hours, Speed and accuracy and work-rate by integrating with the developers working environment.</p>
            <a href="#" class="btn">Join our team</a>
          </div>
          <div class="col-md-6">
            <img src="~/assets/images/Home/Illustration - Remote.svg" alt="Remote is the future" width="100%">
          </div>
        </div>
      </div>
    </section>
    <section id="dev-method">
      <div class="container">
        <div class="row">
          
          <div class="col-md-6">
            <h2 class="mb-5">Our development methodology</h2>
            <h4 class="mb-4">At Natterbase, we have got all the right guns to make your project experience successful and we are not afraid to use it. </h4>
            <p class="mb-3">Our fluid means of execution enables visibility on the side of the client as they can 
              choose the developers they desire based on the skill set that best aligns with their project 
              requirements and most importantly, speed and accuracy on our side.
               </p>

            <p class="mb-5">You can monitor the speed and accuracy of developers, assign tasks to them and monitor
               the progress of your projects. Even better, all your code remains secure and access can be restricted as required.
               </p>
            <a href="#" class="btn">Learn More</a>
          </div>

          <div class="col-md-6">
              <img src="~/assets/images/Home/Illustration - Our Methodologies.svg" alt="Our Methodologies" class="" width="100%">
          </div>
        </div>
      </div>
    </section>
  </div>

</template>
<script>
  import Navbar from '../components/Navbar'
 
  export default {
    components: {
      Navbar
    }
  }
</script>
<style scoped>

  .hero-header {
    height: 700px;
  }

  .hero-header-bottom {
    padding-top: 100px;
  }

  .header-nav {
    background-color: #000;
  }

  .hero-header {
    padding-top: 200px;
    background-color: #000;
    color: #fff;
  }

  h1 {
    font-weight: 200;
  }

  h5 {
    font-weight: 300;
  }

  #about {
    margin-top: 600px;
  }
  @media only screen and (max-width: 768px){
    #about{
      margin-top: 200px;
    }
  }
  #known-for {
    margin-top: 150px;
  }

  h2 {
    color: #000;
  }


  p.about-text {


    max-width: 580px;
  }

  .features-item {
    margin: 100px 0;
  }

  #special {
    padding: 100px 0px;
    background-color: #000;
    color: #fff;
  }
  .sub-text{
    max-width: 600px;
    line-height: 1.5;
  }

  #special h2,
  #special p,
  #special h4 {
    color: #fff;
    ;
  }

  #special h4,
  #work h4 {
    font-weight: 600;
    font-size: 24px;
  }

  #work {
    padding: 100px;
    position: relative;
    top: -100px;
    background-color: #fff;
    margin: 0px 200px;
  }
  #portfolio {
    padding: 100px;
    background-color: #fff;
    margin: 0px 200px;
  }
  #testimonials{
    margin: 100px 0px;
    padding: 100px 200px;
    background-color: #f7f7f7;
   
  }
  #remote, #best-dev, #dev-method{
   padding: 100px 200px; 
  }
  #remote{
    background-color: #f7f7f7;
  }
  p.name{
    padding-bottom: 0px;
    margin-bottom: 0px;
   font-weight: 600;
  }
  @media only screen and (max-width: 768px){
    #remote, #best-dev, #dev-method, #testimonials{
      padding: 100px 50px; 
  }
  .btn{
    width: auto;
  }
  #portfolio, #work{
    margin: 0 50px;
    padding: 30px;
  }
  }
</style>

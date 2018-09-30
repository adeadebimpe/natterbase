<template>
  <div class="about-template">
    <secondNavbar />
    <div class="page-header">
      <div class="container">
        <h1 class="text-center">Contact Us</h1>
      </div>
    </div>
    <section class="contact-header">
      <div class="container">
        <h2 class="text-center mb-5">
          Send us an Email or Call Us
        </h2>
        <p class="text-center">info@natterbase.com</p>
        <p class="text-center">0801 234 5679</p>
      </div>
    </section>
    <section class="contact-form">
      <div class="container">
          <h2 class="text-center mb-5">
          Contact Form
        </h2>
        <form action="">
          <div class="form-group">

            <input type="text" class="form-control" name="" id="" aria-describedby="helpId" placeholder="Your email address">

          </div>
          <div class="form-group">

            <input type="tel" class="form-control" name="" id="" aria-describedby="helpId" placeholder="Your phone number">

          </div>
          <div class="form-group">

            <textarea class="form-control" name="" id="" rows="6" placeholder="How can we help you?"></textarea>
          </div>
          <div class="form-group d-flex justify-content-center">
            <input name="" id="" class="btn" type="button" value="Send Message">
          </div>
        </form>
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
  }

  .bg-grey {
    background-color: #f7f7f7;
  }

  .contact-form{
    margin-top: 70px;
  }
  
  @media only screen and (min-width: 1200px){
    .contact-form form{
    margin: 0px 150px;
  }
  }
  .form-control{	
    border: 1px solid #E4E4E4;	
    background-color: #FFFFFF;
    padding: 20px;
    margin-bottom: 30px;
    }
  ::placeholder{
    color:#A2A2A2;
    font-size: 16px;
    font-weight: 300;
  }
  ::-webkit-input-placeholder{
    color:#A2A2A2;
    font-size: 16px;
    font-weight: 300;
  }
  ::-moz-input-placeholder{
    color:#A2A2A2;
    font-size: 16px;
    font-weight: 300;
  }
</style>

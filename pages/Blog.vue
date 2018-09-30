<template>
  <div class="about-template">
    <secondNavbar />
    <div class="page-header">
      <div class="container">
        <h1 class="text-center">Blog</h1>
      </div>
    </div>
   <section class="blog">
       <div class="container">
           <h2 class="text-center my-5">All Blog Post</h2>
           <div class="row blog-content">
               <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
               </div>
               <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
               </div>
               <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
               </div>
                <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
               </div>
               <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
               </div>
               <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
               </div>
                <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
               </div>
               <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
               </div>
               <div class="col-md-4 blog-item">
                   <h5 class="blog-title">Exception handling in async functions</h5>
                   <p class="blog-date">Aug 28th, 2018</p>
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
  .blog-content{
      margin: 100px 0px;
  }
  .blog-item{
      margin-bottom: 50px;
  }
  h5.blog-title{
      font-size: 20px;
      font-weight: 600;
      margin-bottom:0px;
  }
  p.blog-date{
      font-size: 14px;
      font-weight: 200;
  }
</style>

<template>
  <footer>
    <div class="container">
      <div class="row">
        <div class="col-md-4">
            <img src="~/assets/images/Home/Menu  and Footer-Logo.svg" alt="Logo" width="70%" class="img-fluid">
        </div>
        <div class="col-md-2">
          <ul class="nav flex-column">
            <li class="nav-item">
              <a class="nav-link" href="#">About Zeedas</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Developer Story</a>
            </li>
          </ul>
        </div>
        <div class="col-md-2">
          <ul class="nav flex-column">
            <li class="nav-item">
              <a class="nav-link" href="#">Case Study</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Blog</a>
            </li>

          </ul>
        </div>
        <div class="col-md-4">
          <p>Contact Us</p>
          <p>Want to get updates of our latest products?</p>
          <form action="">
            <div class="input-group mb-3 mt-3">
              <input type="text" class="form-control" placeholder="Your email address" aria-label="Your email address"
                aria-describedby="basic-addon2">
              <div class="input-group-append">
                <span class="input-group-text" id="basic-addon2"><img src="~/assets/images/Home/Footer - Newsletter - Success.svg" alt="Facebook"></span>
              </div>
            </div>
          </form>
          <ul class="social-icons">
             <div class="row">
                 <div class="col-md-3">
                      <a href="#"><img src="~/assets/images/Home/Social - Facebook.svg" alt="Facebook"></a>
                 </div>
                 <div class="col-md-3">
                      <a href="#"><img src="~/assets/images/Home/Social - Twitter.svg" alt="Twitter"></a>
                 </div>
                 <div class="col-md-3">
                      <a href="#"><img src="~/assets/images/Home/Social - Instagram.svg" alt="Instagram"></a>
                 </div>
                 <div class="col-md-3">
                      <a href="#"><img src="~/assets/images/Home/Social - Google+.svg" alt="Google"></a>
                 </div>
             </div>
          </ul>
        </div>
      </div>
      <div class="copyright mt-5">
        <div class="row">
          <div class="col-md-8">
            <hr>
          </div>
          <div class="col-md-4">
            <p> &copy; 2018 Natterbase. All Rights Reserved</p>
          </div>
        </div>
      </div>
    </div>
  </footer>

</template>
<style>
  footer {
    background-color: #000;
    padding: 100px 0px;
  }

  footer ul li a.nav-link,
  footer p {
    color: #fff;
  }
  footer input.form-control{
      background-color: #232323;
      height: 64px;
      border: none;
      border-radius: 0;
  }
footer .input-group-append{
    border-radius: 0;
}
input::placeholder{
   color: #666666;
   text-transform: capitalize;
   font-size: 18px; 
}
::-webkit-input-placeholder { /* Chrome/Opera/Safari */
  color: #666666;
}
::-moz-placeholder { /* Firefox 19+ */
  color: #666666;
}
:-ms-input-placeholder { /* IE 10+ */
  color: #666666;
}
:-moz-placeholder { /* Firefox 18- */
  color: #666666;
}
  .copyright hr {
    border-bottom: 0.5px solid #ffffff;
  }

</style>

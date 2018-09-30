<template>

  <div class="header-nav">
    <div class="container">
      <nav class="navbar navbar-expand-sm|md|lg|-xl navbar-dark">
    <a class="navbar-brand" href="#"><img src="~/assets/images/Home/Menu  and Footer-Logo.svg" alt="Logo"></a>
    <ul class="navbar-nav mr-auto ml-auto flex-row justify-content-between mt-2 nav-right">
            <li class="nav-item active">
                <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Work</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Customer story</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Developer story</a>
            </li>
          
    </ul>
    <button class="navbar-toggler hidden-lg-up" type="button" data-toggle="collapse" data-target="#collapsibleNavId" aria-controls="collapsibleNavId"
        aria-expanded="false" aria-label="Toggle navigation">
        <span class="navbar-toggler-icon"></span>
    </button>
    
    <div class="collapse navbar-collapse" id="collapsibleNavId">
        <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
            <li class="nav-item active">
                <a class="nav-link" href="#">About Zeedas</a>
            </li>
            <li class="nav-item">
                <a class="nav-link" href="#">Pricing</a>
            </li>
             <li class="nav-item">
                <a class="nav-link" href="#">Case Study</a>
            </li>
             <li class="nav-item">
                <a class="nav-link" href="#">Blog</a>
            </li>
             <li class="nav-item">
                <a class="nav-link" href="#">Contact Us</a>
            </li>
          
        </ul>
        
    </div>
</nav>

    </div>
  </div>
</template>
<style>
  .header-nav {
    background-color: #000000;
  }
  .nav-right li{
    padding: 30px 20px;
  }
  .nav-right li a.nav-link{
    color: #fff;
  }
 .navbar-dark .navbar-toggler-icon {
    background-image: url('~/assets/images/Home/Menu - Hamburger - White.svg');
}
@media only screen and (max-width: 991px){
    ul.nav-right{
        display: none;
    }
}
button.navbar-toggler {
    border: none;
}
</style>

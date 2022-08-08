<script>
  import "../global.css";
  import "../app.scss";
</script>

<header>
  <!-- <Title title="Orbisnauta Labs"/> -->

</header>

<nav class="navbar navbar-expand navbar-light bg-light">
 

    <a href="/" class="navbar-brand">
      <img src="images/virtual_reality_ development_agency_orbisnauta_logo.png" class="img-fluid"  alt="" />
    </a>

  <div class="collapse navbar-collapse" id="navbarText">
    <ul class="navbar-nav mr-auto">

      <li class="nav-item ">
        <a class="nav-link " href="/es">ESP</a>
      </li>
    
      <li class="nav-item">
        <a class="nav-link" href="/">ENG</a>
      </li>


  </div>

</nav>

<main>

  <slot>
    
  </slot>

</main>

<footer>
  <section id="footer" class="bg-light d-flex align-items-center">
    <div class="container-lg">
      <div class="row section-body justify-content-center my-1">
        <p> - Copyright Ⓒ 2022 Orbisnauta - </p>
      </div>
    </div>

  </section>
</footer>

<style>

p{
text-align: center;
margin:auto;
}

nav{
  text-align: right;
}

img{
 

  height: 50px;
}

.navbar-brand{

  margin-left: 15px;
  margin-right: 0px;
}

li{
  list-style: none;
}



/* 5) ULTRA LARGE SIZE - ULTRA SCREENS >1921 */
@media(min-width: 1921px){

  
}


/* 4) VERY LARGE SIZE - LARGE SCREENS >1920px and <1400px */
@media(max-width: 1920px) and (min-width: 1400px){


}

/* 3) LARGE SIZE - PC  >1399px and <992px */
@media(max-width: 1399px) and (min-width: 992px){


}

/* 2) MID SIZE - HORIZONTAL TABLETS >991px and <768px */
@media(max-width: 991px) and (min-width: 768px){


}

/* 1) SMALL SIZE - TABLETS AND PHONES <767px*/
@media(max-width: 767px){


}

/* 0) VERY SMALL SIZE - SMALL PHONES <576px*/
@media(max-width: 576px){


}





</style>
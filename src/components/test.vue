<template>
  <header class="header">

    <div class="container">
      <nav class="navbar navbar-expand-lg navbar-dark bg-dark">
        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo01" aria-controls="navbarTogglerDemo01" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarTogglerDemo01">
          <a class="navbar-brand" href="#">Grannate</a>
          <ul class="navbar-nav mr-auto mt-2 mt-lg-0">
            <li class="nav-item active">
              <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Regístrate <span class="sr-only">(current)</span></a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Iniciar Sesión <span class="sr-only">(current)</span></a>
            </li>
          </ul>
          <form class="form-inline my-2 my-lg-0">
            <input class="form-control mr-sm-2" type="search" placeholder="Buscar" aria-label="Search">
            <button type="button" class="btn btn-outline-light">Buscar</button>
          </form>
        </div>
      </nav>
    </div>

    <div class="text-header d-flex align-item-center"> 
      <div class="container">
        <div class="row">
          <div class="col-sm-8">
            <h2> <span></span> </h2>
            <a href="" class="btn btn-yo"><span></span></a>
          </div>
        </div>
      </div>
    </div>

  </header>

</template>

<script>
export default {
}
</script>

<style media="screen">
  
  .header {
  width: 100%;
  min-width: 100vh;
  background-image: url(../assets/fondo.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
}

</style>
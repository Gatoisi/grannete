<template>
    <div class="fondo">
        <div class="container">
            <div class="row">
                <div class="col-sm-12">
                    <div id="mi-slider" class="carousel slide" data-ride="carousel">

                        <!-- indicadores -->


                        <!-- wrappers-->

                        <div class="carousel-inner" role="listbox">
                            <div class="item .active">
                                <img src="../assets/vestido.jpg" alt="vestido"/>
                                <div class="carousel-caption">
                                    <h1>Vestidos</h1>
                                </div>
                            </div>
                            <div class="item ">
                                <img src="../assets/traje.jpg" alt="vestido"/>
                                <div class="carousel-caption">
                                    <h1>Trajes</h1>
                                </div>
                            </div>
                        </div>

                        <!-- controles -->

                        <a class="left carousel-control" href="#mi-slider" role="button" data-slide="prev">
                            <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>
                            <span class="sr-only"> previous </span>
                        </a>
                         <a class="right carousel-control" href="#mi-slider" role="button" data-slide="next">
                            <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>
                            <span class="sr-only"> previous </span>
                        </a>

                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>


export default {
}


</script>

<style media="screen">
  
  .fondo {
  width: 100%;
  min-width: 100vh;
  background-image: url(../assets/fondo.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
}

</style>
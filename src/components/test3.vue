<template>
    <div class="fondo">
        <footer>
            <div class="foother-top">
                <div class="container">
                    <div class="row">
                        <div class="col-md-3 col.sm-6 col-xs-12 segment-one md-mb-30 sm-mb-30">
                            <h3>Grannate</h3>
                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Atque et saepe veritatis minima, magni praesentium, est earum molestias dicta vel facere tempore corrupti perferendis recusandae! Delectus nisi illum quae veniam?</p>
                            <a class="btn btn-block btn-social btn-facebook">
                                <span class="fa fa-twitter"></span> Sign in with Twitter
                            </a>
                        </div>
                        <div class="col-md-3 col.sm-6 col-xs-12 segment-two md-mb-30 sm-mb-30">
                            <h2>titulo</h2>
                            <ul>
                                <li> <a href="#">Evento</a></li>
                                <li> <a href="#">support</a></li>
                                <li> <a href="#">Hosting</a></li>
                                <li> <a href="#">Carrer</a></li>
                                <li> <a href="#">Blog</a></li> 
                            </ul>
                             <a class="btn btn-block btn-social btn-instagram">
                                <span class="fa fa-twitter"></span> Sign in with Twitter
                            </a>
                        </div>
                        <div class="col-md-3 col.sm-6 col-xs-12 segment-three sm-mb-30">
                            <h2>follow us</h2>
                            <p>Lorem ipsum dolor sit, amet consectetur adipisicing elit. Debitis illo quas asperiores reiciendis ab impedit, deserunt nisi repellat facilis ut qui nemo doloribus dolore maiores tenetur modi repudiandae explicabo dolorem?</p>
                            <a class="btn btn-block btn-social btn-google">
                                <span class="fa fa-twitter"></span> Sign in with Twitter
                            </a>
                        </div>
                        <div class="col-md-3 col.sm-6 col-xs-12 segment-four sm-mb-30">
                            <h2>titulo</h2>
                            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea eveniet placeat minus fuga accusamus, porro dignissimos ipsam, eligendi voluptas inventore commodi ipsa velit esse dolor saepe error optio aut quaerat!</p>
                            <form action="">
                                <input type="email">
                                <input type="submit" value="Suscribete">
                            </form>
                        </div>
                    </div>
                </div>
            </div>
            <p class="foother-bottom-text">Todos los derechos reservados por Gatoisi also &copy;Grannate.2020</p>
        </footer>
    </div>
</template>

<script>
export default {
    
}
</script>

<style>

.fondo {
  width: 100%;
  min-width: 100vh;
  background-image: url(../assets/fondo.jpg);
  background-repeat: no-repeat;
  background-position: center;
  background-attachment: fixed;
  background-size: cover;
}

p {
    color: #999;
    line-height: 25px;
}

h2,h3{
    color: #fff;
}

h2{
    font-size: 18px;
}

.foother-top{
    background: #111;
    padding: 80px, 0;

}

.segment-one h3{
    font-family: courgette;
    color: #fff;
    letter-spacing: 3px;
    margin: 10px;
}

.segment-two h2{
    font-family: Poppins;
    color: #fff;
    text-transform: uppercase;
    margin: 10px;
}

.segment-two h2:before {
    content: '|';
    color: #c65039;
    padding-right: 10px;
}

.segment-two ul{
    margin: 0;
    padding: 0;
    list-style: none;
}

.segment-two ul li{
    border-bottom: 1px solid rgba(255, 255, 255, 0.3);
    line-height: 40px;
}

.segment-two ul li a{
    color: #999;
    text-decoration: none;
}

.segment-three h2{
    color: #fff;
    font-family: Poppins;
    text-transform: uppercase;
    margin: 10px;
}

.segment-three h2:before {
    content: '|';
    color: #c65039;
    padding-right: 10px;
}

.segment-four h2{
    color: #fff;
    font-family: Poppins;
    text-transform: uppercase;
    margin: 10px;
}

.segment-four h2:before {
    content: '|';
    color: #c65039;
    padding-right: 10px;
}

.segment-four form input[type=submit]{
    background: #c65039;
    border: none;
    padding: 3px 15px;
    margin-left: -5px;
    color: #fff;
    text-transform: uppercase;
}

.foother-bottom-text{
    text-align: center;
    background: #000;
    line-height: 75px;
}

/* css responsivo */

@media only screen and (min-width: 768px) and (max-width: 991px) {
    .md-mb-30{
        margin-bottom: 30px;

    }
}

@media only screen and (max-width: 767px){
    .sm-mb-30{
        margin-bottom: 30px;
    }
    .foother-top{
        padding: 50px 0;
    }
}

</style>
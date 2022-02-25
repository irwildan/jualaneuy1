<template>
    <main>
        <link href="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
<script src="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
<script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
<!------ Include the above in your HEAD tag ---------->

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.0.10/css/all.css" integrity="sha384-+d0P83n9kaQMCwj8F4RJB66tzIwOKmrdb46+porD/OvrJ+37WqIM7UoBtwHO6Nlg" crossorigin="anonymous">

<div class="row" id="contatti">
<div class="container mt-5" >

    <div class="row" style="height:550px;">
      <div class="col-md-6 maps" >
         <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3957.1843570600913!2d108.23817665043916!3d-7.3331816741348215!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x2e6f59e0c5458ecb%3A0x40a0cda3336fc96b!2sJl.%20Sukasirna%2C%20Sukanagara%2C%20Kec.%20Purbaratu%2C%20Kab.%20Tasikmalaya%2C%20Jawa%20Barat!5e0!3m2!1sid!2sid!4v1645678513643!5m2!1sid!2sid" width="600" height="450" style="border:0;" allowfullscreen="" loading="lazy"></iframe>
      </div>
      <div class="col-md-6">
        <h2 class="text-uppercase mt-3 font-weight-bold text-white">CONTACT</h2>
        <form action="">
          <div class="row">
            <div class="col-lg-6">
              <div class="form-group">
                <input type="text" class="form-control mt-2" placeholder="Nama" required>
              </div>
            </div>
            <div class="col-lg-6">
              <div class="form-group">
                <input type="text" class="form-control mt-2" placeholder="Username" required>
              </div>
            </div>
            <div class="col-lg-6">
              <div class="form-group">
                <input type="email" class="form-control mt-2" placeholder="Email" required>
              </div>
            </div>
            <div class="col-lg-6">
              <div class="form-group">
                <input type="number" class="form-control mt-2" placeholder="Telepon" required>
              </div>
            </div>
            <div class="col-12">
              <div class="form-group">
                <textarea class="form-control" id="exampleFormControlTextarea1" placeholder="Tulis keluhanmu disini" rows="3" required></textarea>
              </div>
            </div>
            <div class="col-12">
            <div class="form-group">
              <div class="form-check">
                <input class="form-check-input" type="checkbox" value="" id="invalidCheck2" required>
                <label class="form-check-label" for="invalidCheck2">
                  Klik Tanda Centang
                </label>
              </div>
            </div>
            </div>
            <div class="col-12">
              <button class="btn btn-light" type="submit">Kirim</button>
            </div>
          </div>
        </form>
        <div class="text-white">
        <h2 class="text-uppercase mt-4 font-weight-bold">Silahkan Hubungi Kami Disini</h2>

        <i class="fas fa-phone mt-3"></i> <a href="tel:+">(+62) 85814390702</a><br>
        <i class="fas fa-phone mt-3"></i> <a href="tel:+">(+62) 85821858135</a><br>
        <i class="fa fa-envelope mt-3"></i> <a href="">wildankecil714@gmail.com</a><br>
        <i class="fas fa-globe mt-3"></i> Kampung Sukasirna, RT 02,RW 05, 46191 Tasikmalaya<br>
        <i class="fas fa-globe mt-3"></i> Kampung Sukasirna, RT 02,RW 05, 46191 Tasikmalaya<br>
        <div class="my-4">
        <a href=""><i class="fab fa-facebook fa-3x pr-4"></i></a>
        <a href=""><i class="fab fa-linkedin fa-3x"></i></a>
        </div>
        </div>
      </div>

    </div>
</div>
</div>

<div class="row text-center bg-success text-white" id="author">
  <div class="col-12 mt-4 h3 ">
  <a href="#">Wildan Pratama</a>
</div>
<div class="col-12 my-2">
<a href="#" target="_blank"><i class="fab fa-linkedin fa-3x"></i></a>
</div>
</div>

    </main>
</template>

<style scoped>
#contatti{
  background-color: #70c3be;
  letter-spacing: 2px;
  }
#contatti a{
  color: #fff;
  text-decoration: none;
}


@media (max-width: 575.98px) {

  #contatti{padding-bottom: 800px;}
  #contatti .maps iframe{
    width: 100%;
    height: 450px;
  }
 }


@media (min-width: 576px) {

   #contatti{padding-bottom: 800px;}

   #contatti .maps iframe{
     width: 100%;
     height: 450px;
   }
 }

@media (min-width: 768px) {

  #contatti{padding-bottom: 350px;}

  #contatti .maps iframe{
    width: 100%;
    height: 850px;
  }
}

@media (min-width: 992px) {
  #contatti{padding-bottom: 200px;}

   #contatti .maps iframe{
     width: 100%;
     height: 700px;
   }
}


#author a{
  color: #fff;
  text-decoration: none;
    
}
</style>
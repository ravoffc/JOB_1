<template>
  <main>
    <link href="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/css/bootstrap.min.css" rel="stylesheet" id="bootstrap-css">
  <script src="//maxcdn.bootstrapcdn.com/bootstrap/4.1.1/js/bootstrap.min.js"></script>
  <script src="//cdnjs.cloudflare.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
  <!------ Include the above in your HEAD tag ---------->

  <!-- CONTACT SECTION -->
    <section id="contact" class="parallax-section">
        <div class="container">
              <div class="row">

                  <div class="col-md-12 col-sm-12">
                        <!-- SECTION TITLE -->
                        <div class="wow fadeInUp section-title" data-wow-delay="0.2s">
                            <h2>Contact Us</h2>
                            <p>fill in the form below correctly !!!</p>
                        </div>
                  </div>

                  <div class="col-md-7 col-sm-10">
                        <!-- CONTACT FORM HERE -->
                        <div class="wow fadeInUp" data-wow-delay="0.4s">
                            <form action="mailto:someone@example.com" id="contact-form" method="post" autocomplete="off">
                                  <div class="col-md-6 col-sm-6">
                                      <input type="text" class="form-control" name="name" placeholder="Name" required="">
                                  </div>
                                  <div class="col-md-6 col-sm-6">
                                      <input type="email" class="form-control" name="email" placeholder="Email" required="">
                                  </div>
                                  <div class="col-md-12 col-sm-12">
                                      <textarea class="form-control" rows="5" name="message" placeholder="Message" required=""></textarea>
                                  </div>
                                  <div class="col-md-offset-8 col-md-4 col-sm-offset-6 col-sm-6">
                                      <button id="submit" type="submit" class="form-control" name="submit">Send Message</button>
                                  </div>
                            </form>
                        </div>
                  </div>

                  <div class="col-md-5 col-sm-8">
                        <!-- CONTACT INFO -->
                        <div class="wow fadeInUp contact-info" data-wow-delay="0.4s">
                            <div class="section-title">
                                  <h2>Contact Info</h2>
                                  <p></p>
                            </div>
                            
                            <p><i class="fa fa-map-marker"></i> West Java, Tasikmalaya City, IND</p>
                            <p><i class="fa fa-comment"></i> <a href="mailto:info@company.com">tarakanalada956@gmail.com</a></p>
                            <p><i class="fa fa-phone"></i> +62 8567-2183-3717</p>
                        </div>
                  </div>

              </div>
        </div>
    </section>
  </main>
</template>

<style scoped>
/*---------------------------------------
  Contact section              
-----------------------------------------*/

.contact-info .fa {
  padding-right: 5px;
}

#contact .form-control {
  border: none;
  border-bottom: 2px solid #f0f0f0;
  border-radius: 0px;
  box-shadow: none;
  font-size: 18px;
  margin-top: 10px;
  margin-bottom: 10px;
  -webkit-transition: all ease-in-out 0.4s;
  transition: all ease-in-out 0.4s;
}

#contact .form-control:focus {
  border-bottom-color: #999999;
}

#contact input {
  height: 55px;
}

#contact button#submit {
  background: #2b2b2b;
  border: none;
  border-radius: 50px;
  color: #ffffff;
  height: 50px;
  margin-top: 24px;
}

#contact button#submit:hover {
  background: #7682cc;
  color: #ffffff;
}


</style>
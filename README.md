# honda-cbr-bootstrap-assignment-Razibul-Alam
code-link : https://github.com/programming-hero-web-course2/honda-cbr-bootstrap-assignment-Razibul-Alam

live-link: https://honda-cbr-bootstrap-raju.netlify.app/


<!-- old -->
 <!doctype html>
<html lang="en">

<head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <!-- Google Fonts -->
    <link
        href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i|Raleway:300,300i,400,400i,500,500i,600,600i,700,700i|Poppins:300,300i,400,400i,500,500i,600,600i,700,700i"
        rel="stylesheet">

    <script src="https://kit.fontawesome.com/2face5b944.js" crossorigin="anonymous"></script>

    <!-- Bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-EVSTQN3/azprG1Anm3QDgpJLIm9Nao0Yz1ztcQTwFspd3yD65VohhpuuCOmLASjC" crossorigin="anonymous">
    <link rel="stylesheet" href="./css/style.css">

    <title>Awesome project</title>
</head>

<body>
    <!-- header section start -->
    
    <!-- header section end -->
   
    <!-- hero section start -->
    <section id="hero" class="container d-flex align-items-center my-5 mt-5">

      <div class="">
          <div class="row">
              <div class="col-lg-6 pt-5 pt-lg-0  order-lg-1 d-flex flex-column ">
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. </p>
                  <h1 class="mb-3">HONDA CBR 300R</h1>
                  <p class="mb-3 text-muted">We are team of talented designers making websites with
                      Bootstrap</p>
                  <div>
                      <button class=" rounded-2 py-2 px-4">Purchase</button>
                  </div>
              </div>
              <div class="col-lg-6 order-lg-2 hero-img" data-aos="fade-left" data-aos-delay="200">
                  <img src="./images/header-bike.png" class="img-fluid animated" alt="">
              </div>
          </div>
      </div>

  </section><!-- End Hero -->

    

     <!--  bag card section start -->
     <section class="shoe pt-5 container">
        <div class="row row-cols-1 row-cols-md-3 g-4">
          
         
          <div class="col p-5">
           <img src="./images/feature-bike.jpg" class="card-img-top" alt="...">
             </div>
          <div class="col p-5">
           <img src="./images/feature-bike.jpg" class="card-img-top" alt="...">
             </div>
          <div class="col p-5">
           <img src="./images/feature-bike.jpg" class="card-img-top" alt="...">
             </div>
        </div>
      </section>
      <!-- bag section end -->

      <!-- casual shoe section start -->
      <section class="casual py-5 my-5">
        <h2 class="my-5">Casual Shoes</h2>
        <div class="row row-cols-1 row-cols-md-3 g-4">
            <div class="col">
              <div class="card h-100 border-0 p-4 shadow-lg rounded-3 text-center">
                <div class="card-img rounded-3 ">
                    <img src="./images/user-1.png" class="w-50" alt="...">
                </div>
                <div class="card-body">
                  <h4 class="card-title">Nike Shoe</h4>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content.</p>
                </div>
                <div class=" d-flex align-items-center justify-content-between card-footer border-0 bg-transparent">
                    <h2>$234</h2>
                    <button type="button" class="btn btn-info px-4"><h5><span><i class="fa fa-shopping-cart p-2" aria-hidden="true"></i></span>Buy now</h5></button>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card h-100 border-0 p-4 shadow-lg rounded-3">
                <div class="card-img rounded-3">
                    <img src="./images/user-2.png" class="card-img-top img-fluid" alt="...">
                </div>
                <div class="card-body">
                  <h4 class="card-title">Nike Shoe</h4>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content.</p>
                </div>
                <div class=" d-flex align-items-center justify-content-between card-footer border-0 bg-transparent">
                    <h2>$234</h2>
                    <button type="button" class="btn btn-info px-4"><h5><span><i class="fa fa-shopping-cart p-2" aria-hidden="true"></i></span>Buy now</h5></button>
                </div>
              </div>
            </div>
            <div class="col">
              <div class="card h-100 border-0 p-4 shadow-lg rounded-3">
                <div class="card-img  rounded-3">
                    <img src="./images/user-3.jpg" class="card-img-top img-fluid" alt="...">
                </div>
                <div class="card-body">
                  <h4 class="card-title">Nike Shoe</h4>
                  <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content.</p>
                </div>
                <div class=" d-flex align-items-center justify-content-between card-footer border-0 bg-transparent">
                    <h2>$234</h2>
                    <button type="button" class="btn btn-info px-4"><h5><span><i class="fa fa-shopping-cart p-2" aria-hidden="true"></i></span>Buy now</h5></button>
                </div>
              </div>
            </div>
            
          </div>

    </section>
    <!-- casual sectio end -->

      <!-- accordion section start -->
<section class="accordion container d-flex align-items-center">
    <section class="row">
        <div class="col-lg-5">
            <img src="./images/faq.png" class="img-fluid" alt="">
        </div>
        <div class="col-lg-7">
            <div class=" container py-3 my-3" id="accordionPanelsStayOpenExample">
                <div class="accordion-item">
                  <h2 class="accordion-header" id="panelsStayOpen-headingOne">
                    <button class="accordion-button" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseOne" aria-expanded="true" aria-controls="panelsStayOpen-collapseOne">
                     Why you choice us?
                    </button>
                  </h2>
                  <div id="panelsStayOpen-collapseOne" class="accordion-collapse collapse show" aria-labelledby="panelsStayOpen-headingOne">
                    <div class="accordion-body">
                      <strong>This is the first item's accordion body.</strong> It is shown by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header" id="panelsStayOpen-headingTwo">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseTwo" aria-expanded="false" aria-controls="panelsStayOpen-collapseTwo">
                      Why we are best in the city?
                    </button>
                  </h2>
                  <div id="panelsStayOpen-collapseTwo" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingTwo">
                    <div class="accordion-body">
                      <strong>This is the second item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                    </div>
                  </div>
                </div>
                <div class="accordion-item">
                  <h2 class="accordion-header" id="panelsStayOpen-headingThree">
                    <button class="accordion-button collapsed" type="button" data-bs-toggle="collapse" data-bs-target="#panelsStayOpen-collapseThree" aria-expanded="false" aria-controls="panelsStayOpen-collapseThree">
                      How will you contact us?
                    </button>
                  </h2>
                  <div id="panelsStayOpen-collapseThree" class="accordion-collapse collapse" aria-labelledby="panelsStayOpen-headingThree">
                    <div class="accordion-body">
                      <strong>This is the third item's accordion body.</strong> It is hidden by default, until the collapse plugin adds the appropriate classes that we use to style each element. These classes control the overall appearance, as well as the showing and hiding via CSS transitions. You can modify any of this with custom CSS or overriding our default variables. It's also worth noting that just about any HTML can go within the <code>.accordion-body</code>, though the transition does limit overflow.
                    </div>
                  </div>
                </div>
              </div>
        </div>

    </section>
</section>


<!-- accordion section end -->
    <!-- count section start -->
    <section class="count container my-5 py-5">
        <div class="counter row d-flex align-items-center">
            <div class="col-lg-5">
                <div class="form-floating mb-3">
                    <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
                    <label for="floatingInput">Email address</label>
                  </div>
                  <div class="form-floating mb-3">
                    <input type="password" class="form-control" id="floatingPassword" placeholder="Password">
                    <label for="floatingPassword">Password</label>
                  </div>
                  <div class="form-floating mb-3">
                    <input type="Text" class="form-control" id="floatingPassword" placeholder="Subject">
                    <label for="floatingPassword">Subject</label>
                  </div>
                  <div class="form-floating mb-3">
                    <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
                    <label for="floatingTextarea2">Comments</label>
                  </div>
                 <div class="cont-btn d-flex justify-content-center">
                    <input class=" rounded-pill bg-primary border-0 px-4 py-3  " type="button"
                    value="Send Message">
                 </div>
            </div>
            <div class="counter-icon col-lg-7">
                <div class="count-1 row">
                    <div class="col-lg-6 d-flex p-2">
                        <h1><i class="far fa-smile icon"></i></h1>
                        <div class="icon-text ms-3">
                            <h1>65</h1>
                            <p>Happy Clients consequuntur voluptas nostrum aliquid ipsam architecto ut.</p>
                        </div>
                    </div>
                    <div class="col-lg-6 d-flex p-2">
                        <h1><i class="far fa-clipboard icon"></i></h1>
                        <div class="icon-text ms-3">
                            <h1>65</h1>
                            <p>Happy Clients consequuntur voluptas nostrum aliquid ipsam architecto ut.</p>
                        </div>
                    </div>
                </div>
                <div class="count-1 row my-3">
                    <div class="col-lg-6 d-flex ">
                        <h1><i class="far fa-clock icon"></i></h1>
                        <div class="icon-text ms-3">
                            <h1>65</h1>
                            <p>Happy Clients consequuntur voluptas nostrum aliquid ipsam architecto ut.</p>
                        </div>
                    </div>
                    <div class="col-lg-6 d-flex ">
                        <h1><i class="fas fa-medal icon"></i></h1>
                        <div class="icon-text ms-3 p-2">
                            <h1>65</h1>
                            <p>Happy Clients consequuntur voluptas nostrum aliquid ipsam architecto ut.</p>
                        </div>
                    </div>
                </div>

            </div>
        </div>

    </section>
<!-- count section end -->
<!-- contact section start -->
<section class="container">
    <h1 class="text-center">Contact Us</h1>
<div class="contact row py-5">
<div class=" social col-lg-4">
    <h2 class="mb-3">My Project</h2>
    <p class="text-muted mb-4">Lorem ipsum dolor sit amet consectetur adipisicing elit. Neque ad alias laboriosam facilis. Aut alias ducimus voluptatibus temporibus. Reiciendis esse aut laudantium eum itaque maxime officiis pariatur cumque ad. Fuga!</p>
    <div class="icon">
        <span><i class="fab fa-facebook"></i></span>
        <span><i class="fab fa-twitter"></i></span>
        <span><i class="fab fa-instagram"></i></span>
        <span><i class="fab fa-linkedin"></i></span>
    </div>

</div>
<div class="inbox col-lg-3 ">
    <div class="cont-icon d-flex align-items-center"><span><i class="fas fa-map-marker-alt"></i></span>
    <p class="ms-3">New York, NY 535022</p></div>
    <div class="cont-icon d-flex align-items-center"><span><i class="far fa-envelope"></i></span>
    <p class="ms-1">info@example.com</p></div>
    <div class="cont-icon d-flex align-items-center"><span><i class="fas fa-phone"></i></span>
    <p class="ms-1">+1 5589 55488 55s</p></div>
</div>
<div class="col-lg-5">
    <div class="form-floating mb-3">
        <input type="email" class="form-control" id="floatingInput" placeholder="name@example.com">
        <label for="floatingInput">Email address</label>
      </div>
      <div class="form-floating mb-3">
        <input type="password" class="form-control" id="floatingPassword" placeholder="Password">
        <label for="floatingPassword">Password</label>
      </div>
      <div class="form-floating mb-3">
        <input type="Text" class="form-control" id="floatingPassword" placeholder="Subject">
        <label for="floatingPassword">Subject</label>
      </div>
      <div class="form-floating mb-3">
        <textarea class="form-control" placeholder="Leave a comment here" id="floatingTextarea2" style="height: 100px"></textarea>
        <label for="floatingTextarea2">Comments</label>
      </div>
     <div class="cont-btn d-flex justify-content-center">
        <input class=" rounded-pill bg-primary border-0 px-4 py-3  " type="button"
        value="Send Message">
     </div>
</div>
</div>
</section>
<!-- contact section end -->
<!-- transfer section start -->
<section class="container">
   <div class="products row d-flex justify-content-center">
    <div class="products-text col-lg-6">
        <h1 class="text-center">Products</h1>
        <p class="text-center">Lorem ipsum dolor sit amet consectetur </p>
    </div>
   </div>
    <div class="transfer row">
        <p class="d-flex justify-content-center">
            <a class="btn btn-primary mx-2" data-bs-toggle="collapse" href="#multiCollapseExample1" role="button" aria-expanded="false" aria-controls="multiCollapseExample1">Shoes</a>
            <button class="btn btn-primary mx-2" type="button" data-bs-toggle="collapse" data-bs-target="#multiCollapseExample2" aria-expanded="false" aria-controls="multiCollapseExample2">Bags</button>

            
          </p>
          <div class="row">
            <div class="collapse multi-collapse" id="multiCollapseExample1">
                <div class="card-group">
                    <div class="card">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This content is a little bit longer.</p>
                      </div>
                      <div class="card-footer">
                        <small class="text-muted">Last updated 3 mins ago</small>
                      </div>
                    </div>
                    <div class="card">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">This card has supporting text below as a natural lead-in to additional content.</p>
                      </div>
                      <div class="card-footer">
                        <small class="text-muted">Last updated 3 mins ago</small>
                      </div>
                    </div>
                    <div class="card">
                      <img src="..." class="card-img-top" alt="...">
                      <div class="card-body">
                        <h5 class="card-title">Card title</h5>
                        <p class="card-text">This is a wider card with supporting text below as a natural lead-in to additional content. This card has even longer content than the first to show that equal height action.</p>
                      </div>
                      <div class="card-footer">
                        <small class="text-muted">Last updated 3 mins ago</small>
                      </div>
                    </div>
                  </div>
              </div>
            <div class="col">
              <div class="collapse multi-collapse" id="multiCollapseExample2">
                <div class="card card-body">
                  Some placeholder content for the second collapse component of this multi-collapse example. This panel is hidden by default but revealed when the user activates the relevant trigger.
                </div>
              </div>
            </div>
          </div>
    </div>
</section>
<!-- transfer section end -->

















    <!-- Optional JavaScript; choose one of the two! -->

    <!-- Option 1: Bootstrap Bundle with Popper -->
    <!-- <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous">
    </script> -->

    <!-- Option 2: Separate Popper and Bootstrap JS -->

    <!-- <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js"
        integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous">
    </script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script>
    <script> -->
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.bundle.min.js" integrity="sha384-MrcW6ZMFYlzcLA8Nl+NtUVF0sA7MsXsP1UyJoMp4YLEuNSfAP+JcXn/tWtIaxVXM" crossorigin="anonymous"></script>


        <script src="https://cdn.jsdelivr.net/npm/@popperjs/core@2.9.2/dist/umd/popper.min.js" integrity="sha384-IQsoLXl5PILFhosVNubq5LC7Qb9DXgDA9i+tQ8Zj3iwWAwPtgFTxbJ8NT4GN1R8p" crossorigin="anonymous"></script>
<!-- <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.0.2/dist/js/bootstrap.min.js" integrity="sha384-cVKIPhGWiC2Al4u+LWgxfKTRIcfu0JTxR+EQDz/bgldoEyl4H0zUF0QKbrJ0EcQF" crossorigin="anonymous"></script> -->

        
       
       
</body>

</html>
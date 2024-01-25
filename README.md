<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Document</title>
    <link rel="stylesheet" href="assets/css/bootstrap.css" />
    <link rel="stylesheet" href="assets/css/fontawesome.pro.6.0.0.css" />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@500;600&family=Quicksand:wght@700&display=swap"
      rel="stylesheet"
    />
    <!-- file style.css la file code luon nam pphai duoi cung -->
    <link rel="stylesheet" href="assets/css/style.css" />
  </head>
  <body>
    <header>
      <nav class="navbar navbar-expand-lg fixed-top main-menu">
        <!-- cua minh thi de sau cung -->
        <div class="container">
          <a class="navbar-brand" href="/">
            <img src="assets/img/logos/logo_light.png" />
          </a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarSupportedContent"
            aria-controls="navbarSupportedContent"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarSupportedContent">
            <ul class="navbar-nav ms-auto">
              <li class="nav-item">
                <a class="nav-link active" href="#home">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#features">Features</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#overview">Overview</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#pricing">Pricing</a>
              </li>
              <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#blog"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Blog
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Blog Grid</a></li>
                  <li><a class="dropdown-item" href="#">Blog Post</a></li>
                </ul>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#subcribe">Subcribe</a>
              </li>
            </ul>
          </div>
        </div>
      </nav>
      <div class="container">
        <section class="banner">
          <div class="box">
            <div class="col-left">
              <h2>Buy Appik for showcase your app wonderful.</h2>
              <p>
                Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo.
              </p>
              <div class="button-group">
                <a class="btn btn-light" href="">
                  <i class="fa-brands fa-apple"></i>
                  App Store</a
                >
                <a class="btn btn-light" href="">
                  <i class="fa-brands fa-google-play"></i>
                  CH Play</a
                >
              </div>
            </div>
            <div class="col-right">
              <img src="assets/img/content/mockup-top.png" alt="" />
            </div>
          </div>
        </section>
      </div>
    </header>
    <main>
      <section id="features">
        <div class="container">
          <div class="heading-main">
            <small> Awesome things </small>
            <h2>Advanced Features & Functions</h2>
          </div>
          <div class="row">
            <!-- Grid -->
            <div class="col-lg-4">
              <div class="item">
                <div class="icon">
                  <i class="fa-solid fa-mobile-notch"></i>
                </div>
                <div class="info">
                  <strong> Easy to Uses </strong>
                  <p class="mt-5">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Vivamus bibendum, nunc ut hendrerit tempus.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4">
              <div class="item">
                <div class="icon">
                  <i class="fa-regular fa-user-shield"></i>
                </div>
                <div class="info">
                  <strong> Modern Design </strong>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Vivamus bibendum, nunc ut hendrerit tempus.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-lg-4">
              <div class="item">
                <div class="icon">
                  <i class="fa-solid fa-credit-card"></i>
                </div>
                <div class="info">
                  <strong> Powerful Options </strong>
                  <p>
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                    Vivamus bibendum, nunc ut hendrerit tempus.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>
      <section id="overview">
        <div class="container">
          <div class="heading-main">
            <h2>Appik for everybody.</h2>
            <small>
              Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do
              eiusmod tempor incididunt ut labore et dolore magna aliqua.
            </small>
          </div>
          <!-- Grid -->
          <div class="row">
            <div class="col-lg-5">
              <img
                class="w-75 m-auto d-block"
                src="assets/img/content/home1.png"
                alt=""
              />
            </div>
            <div class="col-lg-7">
              <div class="heading-main align-left mt-5">
                <h2><strong> Appik </strong>Makes Everything Better.</h2>
                <p class="mt-5">
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
                  do eiusmodtempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam,quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodoconsequat. Duis aute
                  irure dolor in reprehenderit in voluptate velit essecillum
                  dolore eu fugiat nulla pariatur. Excepteur sint occaecat
                  cupidatat nonproident, sunt in culpa qui officia deserunt
                  mollit anim id est laborum.
                </p>
                <div class="button-group">
                  <a class="btn btn-light" href="">
                    <i class="fa-brands fa-apple"></i>
                    App Store</a
                  >
                  <a class="btn btn-light" href="">
                    <i class="fa-brands fa-google-play"></i>
                    CH Play</a
                  >
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-lg-7">
              <div class="heading-main align-left mt-5">
                <h2>Everyone loves <strong>Appik.</strong></h2>
                <p>
                  Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed
                  do eiusmodtempor incididunt ut labore et dolore magna aliqua.
                  Ut enim ad minim veniam,quis nostrud exercitation ullamco
                  laboris nisi ut aliquip ex ea commodo.
                </p>
                
                
                  <ul class="list-unstyled">
                    <li>
                      <i class="fa-solid fa-check"></i>
                      Both iOS and Android should be covered
                    </li>
                    <li>
                      <i class="fa-solid fa-check"></i>
                      Feedback and contact means
                    </li>
                    <li>
                      <i class="fa-solid fa-check"></i>
                      Personalization options & Regular updates
                    </li>
                  </ul>
                  <div class="button-group">
                    <a class="btn btn-light btn-linear-gradient" href=""> Dicover More</a>
                  </div>
              </div>
            </div>
            <div class="col-lg-5">
              <img
                class="w-75 m-auto d-block"
                src="assets/img/content/home2.png"
                alt=""
              />
            </div>
          </div>
          </div>
        </div>
      </section>
      <section id="watch-video">
        <div class="bg-img">
          <h2>Watch Video</h2>
          <div class="icon-box">
            <div class="rounded-box">
              <i class="fa-sharp fa-solid fa-play"></i>
            </div>
          </div>
        </div>
      </section>
      <section id="review">
        <div class="container">
            <div class="heading-main">
                <small>Testmonials</small>
                <h2>Great user reviews</h2>
            </div>
            <div class="testmonials">
                <div id="carousel-review" class="carousel slide"
                     data-bs-ride="carousel" data-bs-keyboard="true" data-bs-pause="false" data-bs-interval="3000">
                    <div class="carousel-indicators">
                        <button type="button" data-bs-target="#carousel-review" data-bs-slide-to="0" class="active" aria-current="true"></button>
                        <button type="button" data-bs-target="#carousel-review" data-bs-slide-to="1"></button>
                        <button type="button" data-bs-target="#carousel-review" data-bs-slide-to="2"></button>
                    </div>
                    <div class="carousel-inner">
                        <div class="carousel-item active">
                          <!-- Grid -->
                            <div class="row">
                                <div class="col-6">
                                    <div class="item">
                                        <div class="item-box">
                                            <img class="avatar" src="assets/img/blog/user-1.png" />
                                            <div class="rating">
                                                <i class="fa-sharp fa-solid fa-star"></i>
                                                <i class="fa-sharp fa-solid fa-star"></i>
                                                <i class="fa-sharp fa-solid fa-star"></i>
                                                <i class="fa-sharp fa-solid fa-star"></i>
                                                <i class="fa-regular fa-star-sharp-half-stroke"></i>
                                            </div>
                                            <div class="title">
                                                for <strong>Features Avaliability</strong>
                                            </div>
                                            <div class="description">
                                                Care through where harold knew all of he scarce to as alone care was fabled objects were friends beyond of sad light tear for in when start and him but
                                            </div>
                                            <div class="author">
                                                <strong>Jonh Doe</strong> - Envator User
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="col-6">
                                    <div class="item"><div class="item-box">
                                      <img class="avatar" src="assets/img/blog/user-2.png" />
                                      <div class="rating">
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-regular fa-star-sharp-half-stroke"></i>
                                      </div>
                                      <div class="title">
                                          for <strong>Powerful Options</strong>
                                      </div>
                                      <div class="description">
                                          Care through where harold knew all of he scarce to as alone care was fabled objects were friends beyond of sad light tear for in when start and him but
                                      </div>
                                      <div class="author">
                                          <strong>Henry</strong> - Appik User
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <div class="carousel-item">
                      <div class="row">
                          <div class="col-6">
                              <div class="item">
                                  <div class="item-box">
                                      <img class="avatar" src="assets/img/blog/user-1.png" />
                                      <div class="rating">
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-regular fa-star-sharp-half-stroke"></i>
                                      </div>
                                      <div class="title">
                                          for <strong>Features Avaliability</strong>
                                      </div>
                                      <div class="description">Care through where harold knew all of he scarce to as alone care was fabled objects were friends beyond of sad light tear for in when start and him but
                                      </div>
                                      <div class="author">
                                          <strong>Jonh Doe</strong> - Envator User
                                      </div>
                                  </div>
                              </div>
                          </div>
                          <div class="col-6">
                              <div class="item">
                                  <div class="item-box">
                                      <img class="avatar" src="assets/img/blog/user-2.png" />
                                      <div class="rating">
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-regular fa-star-sharp-half-stroke"></i>
                                      </div>
                                      <div class="title">
                                          for <strong>Powerful Options</strong>
                                      </div>
                                      <div class="description">
                                          Care through where harold knew all of he scarce to as alone care was fabled objects were friends beyond of sad light tear for in when start and him but
                                      </div>
                                      <div class="author">
                                          <strong>Henry</strong> - Appik User
                                      </div>
                                  </div>
                              </div>
                          </div>
                      </div>
                  </div>
                  <div class="carousel-item">
                      <div class="row">
                          <div class="col-6">
                              <div class="item">
                                  <div class="item-box">
                                      <img class="avatar" src="assets/img/blog/user-1.png" />
                                      <div class="rating">
                                          <i class="fa-sharp fa-solid fa-star"></i><i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-regular fa-star-sharp-half-stroke"></i>
                                      </div>
                                      <div class="title">
                                          for <strong>Features Avaliability</strong>
                                      </div>
                                      <div class="description">
                                          Care through where harold knew all of he scarce to as alone care was fabled objects were friends beyond of sad light tear for in when start and him but
                                      </div>
                                      <div class="author">
                                          <strong>Jonh Doe</strong> - Envator User
                                      </div>
                                  </div>
                              </div>
                          </div>
                          <div class="col-6">
                              <div class="item">
                                  <div class="item-box">
                                      <img class="avatar" src="assets/img/blog/user-2.png" />
                                      <div class="rating">
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-sharp fa-solid fa-star"></i>
                                          <i class="fa-regular fa-star-sharp-half-stroke"></i>
                                      </div>
                                      <div class="title">
                                          for <strong>Powerful Options</strong>
                                      </div>
                                      <div class="description">
                                          Care through where harold knew all of he scarce to as alone care was fabled objects were friends beyond of sad light tear for in when start and him but
                                      </div>
                                      <div class="author">
                                          <strong>Henry</strong> - Appik User
                                      </div>
                                  </div>
                                </div>
                              </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>
    </main>
    <footer>
      <center>chaan ttranh</center>
    </footer>
    <section id="script">
      <script src="assets/js/bootstrap.bundle.js"></script>
      <script src="assets/js/script.js"></script>
    </section>
  </body>
</html>

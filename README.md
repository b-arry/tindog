<!DOCTYPE html>
<html>

<head>
  <meta charset="utf-8">
  <title>TinDog</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css?family=Montserrat|Ubuntu" rel="stylesheet">

  <!-- CSS Stylesheets -->
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
  <link rel="stylesheet" href="css/styles.css">

  <!-- Font Awesome -->
  <script defer src="https://use.fontawesome.com/releases/v5.0.7/js/all.js"></script>

  <!-- Bootstrap Scripts -->
  <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
</head>

<body>

  <section class="colored-section" id="title">

    <div class="container-fluid">

      <!-- Nav Bar -->

      <nav class="navbar navbar-expand-lg navbar-dark">

        <a class="navbar-brand" href="">tindog</a>

        <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarTogglerDemo02">
            <span class="navbar-toggler-icon"></span>
        </button>

        <div class="collapse navbar-collapse" id="navbarTogglerDemo02">

          <ul class="navbar-nav ml-auto">
            <li class="nav-item">
              <a class="nav-link" href="#footer">Contact</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#pricing">Pricing</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#cta">Download</a>
            </li>
          </ul>

        </div>
      </nav>


      <!-- Title -->

      <div class="row">

        <div class="col-lg-6">
          <h1 class="big-heading">Meet new and interesting dogs nearby.</h1>
          <button type="button" class="btn btn-dark btn-lg download-button"><i class="fab fa-apple"></i> Download</button>
          <button type="button" class="btn btn-outline-light btn-lg download-button"><i class="fab fa-google-play"></i> Download</button>
        </div>

        <div class="col-lg-6">
          <img class="title-image" src="TinDog Completed Website/images/iphone6.png" alt="iphone-mockup">
        </div>

      </div>

    </div>

  </section>


  <!-- Features -->

  <section class="white-section" id="features">

    <div class="container-fluid">

      <div class="row">
        <div class="feature-box col-lg-4">
          <i class="icon fas fa-check-circle fa-4x"></i>
          <h3 class="feature-title">Easy to use.</h3>
          <p>So easy to use, even your dog could do it.</p>
        </div>

        <div class="feature-box col-lg-4">
          <i class="icon fas fa-bullseye fa-4x"></i>
          <h3 class="feature-title">Elite Clientele</h3>
          <p>We have all the dogs, the greatest dogs.</p>
        </div>

        <div class="feature-box col-lg-4">
          <i class="icon fas fa-heart fa-4x"></i>
          <h3 class="feature-title">Guaranteed to work.</h3>
          <p>Find the love of your dog's life or your money back.</p>
        </div>
      </div>


    </div>
  </section>


  <!-- Testimonials -->

  <section class="colored-section" id="testimonials">

    <div id="testimonial-carousel" class="carousel slide" data-ride="false">
      <div class="carousel-inner">
        <div class="carousel-item active container-fluid">
          <h2 class="testimonial-text">I no longer have to sniff other dogs for love. I've found the hottest Corgi on TinDog. Woof.</h2>
          <img class="testimonial-image" src="TinDog Completed Website/images/dog-img.jpg" alt="dog-profile">
          <em>Pebbles, New York</em>
        </div>
        <div class="carousel-item container-fluid">
          <h2 class="testimonial-text">My dog used to be so lonely, but with TinDog's help, they've found the love of their life. I think.</h2>
          <img class="testimonial-image" src="TinDog Completed Website/images/lady-img.jpg" alt="lady-profile">
          <em>Beverly, Illinois</em>
        </div>
      </div>
      <a class="carousel-control-prev" href="#testimonial-carousel" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon"></span>
      </a>
      <a class="carousel-control-next" href="#testimonial-carousel" role="button" data-slide="next">
    <span class="carousel-control-next-icon"></span>
      </a>
    </div>

  </section>


  <!-- Press -->

  <section class="colored-section" id="press">
    <img class="press-logo" src="TinDog Completed Website/images/techcrunch.png" alt="tc-logo">
    <img class="press-logo" src="TinDog Completed Website/images/tnw.png" alt="tnw-logo">
    <img class="press-logo" src="TinDog Completed Website/images/bizinsider.png" alt="biz-insider-logo">
    <img class="press-logo" src="TinDog Completed Website/images/mashable.png" alt="mashable-logo">

  </section>


  <!-- Pricing -->

  <section class="white-section" id="pricing">

    <h2 class="section-heading">A Plan for Every Dog's Needs</h2>
    <p>Simple and affordable price plans for your and your dog.</p>

    <div class="row">

      <div class="pricing-column col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Chihuahua</h3>
          </div>
          <div class="card-body">
            <h2 class="price-text">Free</h2>
            <p>5 Matches Per Day</p>
            <p>10 Messages Per Day</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-outline-dark" type="button">Sign Up</button>
          </div>
        </div>
      </div>

      <div class="pricing-column col-lg-4 col-md-6">
        <div class="card">
          <div class="card-header">
            <h3>Labrador</h3>
          </div>
          <div class="card-body">
            <h2 class="price-text">$49 / mo</h2>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>
          </div>
        </div>
      </div>

      <div class="pricing-column col-lg-4">
        <div class="card">
          <div class="card-header">
            <h3>Mastiff</h3>
          </div>
          <div class="card-body">
            <h2 class="price-text">$99 / mo</h2>
            <p>Pirority Listing</p>
            <p>Unlimited Matches</p>
            <p>Unlimited Messages</p>
            <p>Unlimited App Usage</p>
            <button class="btn btn-lg btn-block btn-dark" type="button">Sign Up</button>

          </div>
        </div>
      </div>



    </div>

  </section>


  <!-- Call to Action -->

  <section class="colored-section" id="cta">

    <div class="container-fluid">

      <h3 class="big-heading">Find the True Love of Your Dog's Life Today.</h3>
      <button class="download-button btn btn-lg btn-dark" type="button"><i class="fab fa-apple"></i> Download</button>
      <button class="download-button btn btn-lg brn-light" type="button"><i class="fab fa-google-play"></i> Download</button>
    </div>
  </section>


  <!-- Footer -->

  <footer class="white-section" id="footer">
    <div class="container-fluid">
      <i class="social-icon fab fa-facebook-f"></i>
      <i class="social-icon fab fa-twitter"></i>
      <i class="social-icon fab fa-instagram"></i>
      <i class="social-icon fas fa-envelope"></i>
      <p>© Copyright 2018 TinDog</p>
    </div>
  </footer>


</body>

</html>



body {
  font-family: "Montserrat";
  text-align: center;
}

h1, h2, h3, h4, h5, h6 {
  font-family: "Montserrat-Bold";
}

p {
  color: #8f8f8f;
}

/* Headings */

.big-heading {
  font-family: "Montserrat-Black";
  font-size: 3.5rem;
  line-height: 1.5;
}

.section-heading {
  font-size: 3rem;
  line-height: 1.5;
}

/* Containers */

.container-fluid{
  padding: 7% 15%;
}

/* Sections */

.colored-section {
  background-color: #ff4c68;
  color: #fff;
}

.white-section {
  background-color: #fff;
}

/* Navigation Bar */

.navbar {
  padding: 0 0 4.5rem;
}

.navbar-brand {
  font-family: "Ubuntu";
  font-size: 2.5rem;
  font-weight: bold;
}

.nav-item {
  padding: 0 18px;
}

.nav-link {
  font-size: 1.2rem;
  font-family: "Montserrat-Light";
}

/* Buttons */

.download-button {
  margin: 5% 3% 5% 0;
}

/* Title Section */

#title {
  background-color: #ff4c68;
  color: #fff;
  text-align: left;
}

#title .container-fluid {
  padding: 3% 15% 7%;
}

/* Title Image */

.title-image {
  width: 60%;
  transform: rotate(25deg);
  position: absolute;
  right: 30%;
}

/* Features Section */

#features {
  position: relative;
}

.feature-title {
  font-size: 1.5rem;
}

.feature-box {
  padding: 4.5%;
}

.icon {
  color: #ef8172;
  margin-bottom: 1rem;
}

.icon:hover {
  color: #ff4c68;
}

/* Testimonial Section */

#testimonials {
  background-color: #ef8172;
}

.testimonial-text {
  font-size: 3rem;
  line-height: 1.5;
}

.testimonial-image {
  width: 10%;
  border-radius: 100%;
  margin: 20px;
}


#press {
  background-color: #ef8172;
  padding-bottom: 3%;
}

.press-logo {
  width: 15%;
  margin: 20px 20px 50px;
}

/* Pricing Section */

#pricing {
  padding: 100px;
}

.price-text {
  font-size: 3rem;
  line-height: 1.5;
}

.pricing-column {
  padding: 3% 2%;
}

/* CTA Section */


/* Footer Section */


.social-icon {
  margin: 20px 10px;
}

@media (max-width: 1028px) {

  #title {
    text-align: center;
  }

  .title-image {
    position: static;
    transform: rotate(0);
  }
}

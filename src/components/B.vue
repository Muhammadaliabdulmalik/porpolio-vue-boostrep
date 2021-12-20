<template>
  <!-- todo navbar -->
  <nav class="navbar navbar-expand-lg navbar-dark fixed-top navigation-bar">
    <div class="container">
      <a class="navbar-brand logo" href="#">MY COMPANY</a>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarSupportedContent"
        aria-controls="navbarSupportedContent"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>

      <div class="collapse navbar-collapse menu" id="navbarSupportedContent">
        <ul class="navbar-nav ml-auto box-ul">
          <li class="nav-item box-li">
            <a class="nav-link box-a" href="#">Home</a>
          </li>
          <li class="nav-item box-li">
            <a class="nav-link box-a" href="#">About Us</a>
          </li>
          <li class="nav-item box-li">
            <a class="nav-link box-a" href="#">Gallery</a>
          </li>
          <li class="nav-item box-li">
            <a class="nav-link box-a" href="#">Testimonial</a>
          </li>
          <li class="nav-item box-li">
            <a class="nav-link box-a" href="#">Contact Us</a>
          </li>
        </ul>
      </div>
    </div>
  </nav>
  <!-- todo navbar -->

  <!-- todo Jumbotron -->
  <div class="jumbotron jumbotron-fluid">
    <div class="container">
      <div class="row">
        <div class="col d-flex justify-content-center align-items-center">
          <h1 class="display-4">COMPANY PROFILE</h1>
        </div>
      </div>
    </div>
  </div>
  <!-- todo Jumbotron -->

  <!-- todo About Us -->
  <div class="about">
    <div class="container">
      <div class="row box-about">
        <div class="col box-about-col">
          <h1>About Us</h1>
        </div>
        <div class="row box-about">
          <div class="col-md text-center box-about-col">
            <img
              src="./assets/img/image-about.jpg"
              alt=""
              class="about-image"
            />
          </div>
          <div class="col-md box-about d-flex align-items-center">
            <p>
              Lorem ipsum dolor sit amet consectetur adipisicing elit. Excepturi
              optio voluptates necessitatibus, tempora accusamus molestiae nobis
              natus, ut similique reiciendis asperiores id modi soluta! Itaque
              vel libero doloremque aut aspernatur corporis aperiam consectetur
              quidem, fugiat deleniti quasi alias distinctio, facere minus?
              Fugiat quidem, qui voluptatibus quam voluptates expedita possimus
              eos aspernatur tempora sit atque placeat nulla cumque veritatis
              repellendus dolor recusandae quas, perferendis praesentium
              deleniti sapiente consequatur ratione et rerum! Velit eum pariatur
              ex at qui animi molestiae commodi beatae?
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- todo About Us -->

  <!-- todo Gallery -->
  <div class="gallery">
    <div class="container">
      <div class="row">
        <div class="col text-center">
          <h1>Gallery</h1>
        </div>
      </div>
      <div class="row">
        <div class="col-md">
          <img
            src="assets/img/gallery/bady-abbas-jOmBUCtflWA-unsplash.jpg"
            alt=""
            class="gallery-image"
          />
        </div>
        <div class="col-md">
          <img
            src="assets/img/gallery/christopher-gower-m_HRfLhgABo-unsplash.jpg"
            alt=""
            class="gallery-image"
          />
        </div>
        <div class="col-md">
          <img
            src="assets/img/gallery/clement-helardot-95YRwf6CNw8-unsplash.jpg"
            alt=""
            class="gallery-image"
          />
        </div>
      </div>
      <div class="row">
        <div class="col-md">
          <img
            src="assets/img/gallery/jay-zhang-ycZjz2Uw6VY-unsplash.jpg"
            alt=""
            class="gallery-image"
          />
        </div>
        <div class="col-md">
          <img
            src="assets/img/gallery/kari-shea-1SAnrIxw5OY-unsplash.jpg"
            alt=""
            class="gallery-image"
          />
        </div>
        <div class="col-md">
          <img
            src="assets/img/gallery/pedro-costa-aXY5doQNZTc-unsplash.jpg"
            alt=""
            class="gallery-image"
          />
        </div>
      </div>
    </div>
  </div>
  <!-- todo Gallery -->

  <!-- todo Testimonial -->
  <div class="testimonial">
    <div class="container">
      <div class="row">
        <div class="col-md">
          <div class="card">
            <img
              src="./assets/img/tetimonial/testi1.jpg"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md">
          <div class="card">
            <img
              src="./assets/img/tetimonial/testi2.jpg"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
          </div>
        </div>
        <div class="col-md">
          <div class="card">
            <img
              src="./assets/img/tetimonial/testi3.jpg"
              class="card-img-top"
              alt="..."
            />
            <div class="card-body">
              <p class="card-text">
                Some quick example text to build on the card title and make up
                the bulk of the card's content.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
  <!-- todo Testimonial -->

  <!-- todo Contact Us -->
  <div class="contact">
    <div class="container">
      <div class="row">
        <div class="col text-center mt-5">
          <h1>Contact Us</h1>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6 mx-auto mt-5">
          <form>
            <div class="form-group">
              <label for="name">Username</label>
              <input type="text" class="form-control" id="name" />
            </div>
            <div class="form-group">
              <label for="email">Email address</label>
              <input
                type="email"
                class="form-control"
                id="email"
                aria-describedby="emailHelp"
              />
            </div>
            <div class="form-group">
              <label for="password">Password</label>
              <input type="password" class="form-control" id="password" />
            </div>
            <button type="submit" class="btn btn-primary">Submit</button>
          </form>
        </div>
      </div>
    </div>
  </div>
  <!-- todo Contact Us -->

  <!-- todo footer -->
  <footer>
    <p class="text-center">&copy; Copyright by Diky Prayoga 2021</p>
  </footer>
  <!-- todo footer -->

  <!-- Optional JavaScript; choose one of the two! -->

  <!-- Option 1: jQuery and Bootstrap Bundle (includes Popper) -->
  <script
    src="https://cdn.jsdelivr.net/npm/jquery@3.5.1/dist/jquery.slim.min.js"
    integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj"
    crossorigin="anonymous"
  ></script>
  <script
    src="https://cdn.jsdelivr.net/npm/bootstrap@4.6.1/dist/js/bootstrap.bundle.min.js"
    integrity="sha384-fQybjgWLrvvRgtW6bFlB7jaZrFsaBXjsOMm/tB9LTS58ONXgqbR9W8oWht/amnpF"
    crossorigin="anonymous"
  ></script>

  <script src="js/script.js">
    dadad
  </script>
</template>

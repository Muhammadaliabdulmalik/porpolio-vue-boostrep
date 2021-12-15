<template>
  <div>
    <!-- navbar -->
    <nav class="navbar fixed-top navbar-expand-lg navbar-dark bg-dark">
      <div class="container">
        <div class="container-fluid">
          <a class="navbar-brand" href="#">Navbar</a>
          <button
            class="navbar-toggler"
            type="button"
            data-bs-toggle="collapse"
            data-bs-target="#navbarNav"
            aria-controls="navbarNav"
            aria-expanded="false"
            aria-label="Toggle navigation"
          >
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="collapse navbar-collapse" id="navbarNav">
            <ul class="navbar-nav">
              <li class="nav-item">
                <a class="nav-link active" aria-current="page" href="#">Home</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Features</a>
              </li>
              <li class="nav-item">
                <a class="nav-link" href="#">Pricing</a>
              </li>
              <li class="nav-item">
                <a class="nav-link disabled">Disabled</a>
              </li>
            </ul>
          </div>
        </div>
      </div>
    </nav>
    <!-- navbar -->

    <div class="jumbotron jumbotron-fluid">
      <div class="container tex-center">
        <img src="../assets/1.png" width="300" class="rounded-circle" />
        <h1 class="display-4">SELAMAT DATANG</h1>
        <p class="lead">SISWA SISWI SMKN15 BANDUNG</p>
      </div>
    </div>

    <div class="container">
      <div class="row">
        <div class="col text-center">
          <h1>about</h1>
        </div>
      </div>
      <div class="row">
        <div class="col">
          <p>
            Use our powerful mobile-first flexbox grid to build layouts of all
            shapes and sizes thanks to a twelve column system, five default
            responsive tiers, Sass variables and mixins, and dozens of
            predefined classes.
          </p>
        </div>
        <div class="col">
          <p>
            Use our powerful mobile-first flexbox grid to build layouts of all
            shapes and sizes thanks to a twelve column system, five default
            responsive tiers, Sass variables and mixins, and dozens of
            predefined classes.
          </p>
        </div>
      </div>
    </div>
    <div class="container">
      <div class="row">
        <div class="col">
          <h1>porfolio</h1>
        </div>
      </div>
      <div class="row">
        <div class="col-md">
          <div class="card">
            <img
              class="card-img-top"
              src="../assets/1.png"
              alt="Card image cap"
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
              class="card-img-top"
              src="../assets/1.png"
              alt="Card image cap"
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
              class="card-img-top"
              src="../assets/1.png"
              alt="Card image cap"
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
      <div class="row">
        <div class="col-md">
          <div class="card">
            <img
              class="card-img-top"
              src="../assets/1.png"
              alt="Card image cap"
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
              class="card-img-top"
              src="../assets/1.png"
              alt="Card image cap"
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
              class="card-img-top"
              src="../assets/1.png"
              alt="Card image cap"
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
</template>
<script>
export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
};
</script>

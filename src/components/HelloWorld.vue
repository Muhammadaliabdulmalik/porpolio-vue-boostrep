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
        <img src="../assets/1.png" width="20%" class="rounded-circle" />
        <h1 class="display-4">SELAMAT DATANG</h1>
        <p class="lead">SISWA SISWI SMKN15 BANDUNG</p>
      </div>
    </div>
    <section id="about" class="about">
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
    </section>
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
    <section id="contac" class="contac">
      <div class="container">
        <div class="row pt-4 mb-4">
          <div class="col text-center">
            <h1>contac us</h1>
          </div>
        </div>
        <div class="row">
          <div class="col-lg-4">
            <div class="card text-white bg-primary mb-3 text-center">
              <div class="card-body">
                <h5 class="card-title">contac us</h5>
                <p class="card-text">
                  Some quick example text to build on the card title and make up
                  the bulk of the card's content.
                </p>
              </div>
            </div>
            <ul class="list-group">
              <li class="list-group-item">Cras justo odio</li>
              <li class="list-group-item">Dapibus ac facilisis in</li>
              <li class="list-group-item">Morbi leo risus</li>
              <li class="list-group-item">Porta ac consectetur ac</li>
              <li class="list-group-item">Vestibulum at eros</li>
            </ul>
          </div>
          <div class="col-lg-6">
            <form>
              <div class="form-group">
                <label for="nama">nama</label>
                <input
                  type="text"
                  class="form-control"
                  width="100%"
                  id="nama"
                  placeholder="nama"
                />
              </div>
              <div class="form-group">
                <label for="email">email</label>
                <input
                  type="text"
                  class="form-control"
                  id="email"
                  placeholder="email"
                />
              </div>
              <div class="form-group">
                <label for="no telp">no telp</label>
                <input
                  type="text"
                  class="form-control"
                  id="no telp"
                  placeholder="no telp"
                />
              </div>
              <div class="form-group">
                <label for="pesan">pesan</label>
                <textarea type="text" class="form-control"></textarea>
              </div>
              <div class="form-group">
                <button type="button" class="btn btn-primary">
                  kirim pesan
                </button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </section>
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
<style scoped></style>

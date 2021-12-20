<template>
  <div>
    <nav class="navbar fixed-top navbar-expand-md">
      <div class="container">
        <a class="navbar-brand" href="#">Mars</a>
        <button
          class="navbar-toggler"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"> </span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <a class="nav-link" href="#"
              >Home <span class="sr-only">(current)</span></a
            >
            <a class="nav-link" href="#">About</a>
            <a class="nav-link" href="#">Portfolio</a>
            <a class="nav-link" href="#">Contact</a>
          </div>
        </div>
      </div>
    </nav>
    <div class="hero">
      <div class="jumbotron jumbotron-fluid">
        <div class="text">
          <img src="../assets/2.jpg" width="20%" />
          <div class="texttitle">
            <h1 class="display-4">Jepang</h1>
            <p class="lead">
              This is a modified jumbotron that occupies the entire horizontal
              space of its parent.
            </p>
          </div>
        </div>
      </div>
    </div>

    <section id="About">
      <div class="aboutbox">
        <div class="container about">
          <div class="row">
            <div class="col">
              <h2>About</h2>
            </div>
          </div>
        </div>
      </div>

      <div class="row text-white">
        <div class="col">
          <img src="../assets/river.jpg" class="images-about" />
        </div>
        <div class="col-md about-box1">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Vero nulla
            officiis tempore laboriosam! Reiciendis doloribus culpa, ipsa
            tempora iure eos fugiat voluptatem facilis aliquam voluptates
            ratione tenetur harum voluptatibus sapiente.
          </p>
        </div>
      </div>
    </section>

    <section id="Portfolio">
      <div class="Portfoliobox">
        <div class="container Portfolio">
          <div class="row md-4">
            <div class="col">
              <h2>Portfolio</h2>
            </div>
          </div>

          <div class="row">
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/mountain.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <div class="card-body">
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/sea.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <div class="card-body">
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/river.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <div class="card-body">
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
          </div>
          <div class="row">
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/mountain.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <div class="card-body">
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/sea.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <div class="card-body">
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/river.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <div class="card-body">
                  <p class="card-text">
                    Some quick example text to build on the card title and make
                    up the bulk of the card's content.
                  </p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
<script>
export default {
  name: "Training",
};
</script>

<style scoped>
.about {
  padding-bottom: 20px;
}
.Portfolio {
  padding-top: 200px;
  padding-bottom: 250px;
}
.jumbotron {
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("../assets/river.jpg");
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  height: 100vh;
}
.navbar {
  background-color: black;
  font-size: 25px;
  font-weight: bold;
  font-family: "Times New Roman", Times, serif;
}
.nav-link {
  color: white;
}
.navbar-brand {
  color: white;
  font-family: "Times New Roman", Times, serif;
  font-size: 40px;
  text-align: left;
}
.nav-link:hover {
  background-color: white;
  border-radius: 50px;
}
.jumbotron {
  margin-bottom: 0;
  padding-top: 100px;
}
.text {
  padding-bottom: 100px;
  color: black;
}
.Portfolio h2 {
  padding-bottom: 50px;
  font-weight: bold;
  font-size: 50px;
  font-family: "Times New Roman";
  color: white;
}
.about h2 {
  padding-bottom: 50px;
  font-weight: bold;
  font-size: 50px;
  color: white;
}
.hero {
  background-color: black;
}
.Portfolio h1 {
  color: white;
}
.card {
  background-color: black;
}
.texttitle {
  padding-top: 100px;
  color: white;
}
.display-4 {
  font-size: 90px;
  font-weight: bold;
  padding-left: 50px;
  font-family: "arialblack";
  color: white;
}
.lead {
  font-size: 40px;
  font-family: "Times New Roman", Times, serif;
}
.img-thumbnail {
  background-color: black;
  padding: 5px;
}

.list-group {
  color: white;
}
.card {
  background-color: black;
}
.ContactBox {
  background-color: black;
}
.form-control {
  background-color: white;
}
.aboutbox {
  color: white;
  padding-top: 50px;
}
.images-about {
  margin-bottom: 100px;
  width: 100%;
}
.about-box1 {
  padding-top: 250px;
}
.card-body {
  background-color: white;
}
#About {
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("../assets/mountain.jpg");
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  height: 100vh;
  width: 100%;
}
#Portfolio {
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("../assets/sea.jpg");
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  height: 200vh;
  width: 100%;
}
@media (max-width: 768px) {
  .display-4 {
    font-size: 50px;
  }

  #About {
    width: 100%;
  }

  #About .row {
    width: 100%;
  }
  #About .about-box2 {
    width: 100%;
    margin: 0;
    padding: 0;
  }

  /* #About .about-box2 .p{

  } */
}
</style>

<template>
  <div id="Home">
    <nav class="navbar navbar-expand-lg fixed-top navigation-bar">
      <div class="container">
        <a class="navbar-brand boxbrand" href="#Mars"><h1>Mars</h1></a>
        <button
          class="navbar-toggler navbar-light"
          type="button"
          data-toggle="collapse"
          data-target="#navbarNav"
          aria-controls="navbarNav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav">
            <li class="nav-item active">
              <a class="nav-link" href="#Home"
                >Home <span class="sr-only">(current)</span></a
              >
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#About">About Us</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#Gallery">Gallery</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#Testimonial">Testimonial</a>
            </li>
            <li class="nav-item active">
              <a class="nav-link" href="#Contact">Contact Us</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <div class="hero">
      <div class="jumbotron jumbotron-fluid">
        <div class="texttitle">
          <h1 class="display-4">Company Profile</h1>
        </div>
      </div>
    </div>

    <section id="About">
      <div class="aboutbox">
        <div class="container about">
          <div class="row pt-5">
            <div class="col">
              <h2>About Us</h2>
            </div>
          </div>
        </div>
      </div>

      <div class="row text-white d-flex align-items-center aboutrow2">
        <div class="col-md">
          <img src="../assets/5.jpg" class="images-about" />
        </div>
        <div class="col-md about-box1">
          <p>
            Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eveniet
            harum esse ex. Doloremque reprehenderit inventore possimus non
            tempora tempore aspernatur est soluta in neque rem qui, itaque,
            repudiandae saepe. Quaerat eum eaque eos autem magnam ullam natus
            hic perferendis eligendi, cupiditate possimus sint dolores ut
            inventore delectus laborum voluptates non.
          </p>
        </div>
      </div>
    </section>

    <section id="Gallery">
      <div class="Gallerybox">
        <div class="container Gallery">
          <div class="row md-4">
            <div class="col">
              <h2>Gallery</h2>
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
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/sea.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/river.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
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
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/sea.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/river.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="Testimonial">
      <div class="container">
        <div class="container Testimonial">
          <div class="row">
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/testi1.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <p>
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                  Culpa placeat est impedit obcaecati exercitationem tempora ex
                  quas nam. Ab, minus!
                </p>
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/testi2.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <p>
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                  Culpa placeat est impedit obcaecati exercitationem tempora ex
                  quas nam. Ab, minus!
                </p>
              </div>
            </div>
            <div class="col-md">
              <div class="card">
                <img
                  src="../assets/testi3.jpg"
                  class="card-img-top"
                  alt="Card image cap"
                />
                <p>
                  Lorem ipsum dolor, sit amet consectetur adipisicing elit.
                  Culpa placeat est impedit obcaecati exercitationem tempora ex
                  quas nam. Ab, minus!
                </p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="Contact">
      <div class="container boxContact">
        <div class="row">
          <div class="col">
            <h2>Contact Us</h2>
          </div>
        </div>

        <div class="row">
          <div class="col-md-8 mx-auto">
            <form>
              <div class="form-group">
                <label for="exampleInputEmail1">Username</label>
                <input
                  type="Username"
                  class="form-control"
                  id="exampleInputEmail1"
                  aria-describedby="emailHelp"
                />
              </div>
              <div class="form-group">
                <label for="exampleInputPassword1">Email Address</label>
                <input
                  type="Email Address"
                  class="form-control"
                  id="exampleInputPassword1"
                />
              </div>
              <div class="form-group">
                <label for="exampleInputPassword1">Password</label>
                <input
                  type="Password"
                  class="form-control"
                  id="exampleInputPassword1"
                />
              </div>
              <button
                type="submit"
                class="btn btn-primary d-flex justify-content-start"
              >
                Submit
              </button>
            </form>
          </div>
        </div>
      </div>
    </section>
    <section id="Footer">
      <div class="container text1">
        <p>©Copyright by Mars 2021</p>
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
.navigation-bar.muncul {
  transition: 0.5s;
  opacity: 1;
  background-color: #192a56;
}

#Contact form input {
  background-color: transparent;
}
#Contact h2 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 50px;
  color: rgba(255, 255, 255, 0.4);
  text-shadow: 0 0 10px rgb(0 0 0 / 20%);
  text-align: center;
}
label {
  color: white;
}
.text1 {
  color: white;
}
form {
  padding: 100px;
}
.boxContact {
  padding: 100px 0 0 0;
}
.about {
  padding-bottom: 20px;
}
.Portfolio {
  padding-top: 100px;
  height: 100%;
}
.jumbotron {
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("../assets/3.jpg");
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  height: 110vh;
}
.navbar {
  background-color: transparent;
  font-size: 25px;
  font-weight: bold;
  font-family: Arial, Helvetica, sans-serif;
  z-index: 1;
}
.nav-item {
  color: white;
}
.boxbrand {
  color: rgba(255, 255, 255, 0.4);
  font-family: Arial, Helvetica, sans-serif;
}
.nav-link {
  color: rgba(255, 255, 255, 0.4);
}
.nav-link:hover {
  background-color: rgba(255, 255, 255, 0.4);
  border-radius: 50px;
}
.jumbotron {
  margin-bottom: 0;
  padding-top: 100px;
}
.Gallery h2 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 50px;
  color: rgba(255, 255, 255, 0.4);
  text-shadow: 0 0 10px rgb(0 0 0 / 20%);
  text-align: center;
  padding-bottom: 80px;
}
.about h2 {
  padding-bottom: 50px;
  font-weight: bold;
  font-size: 50px;
  color: rgba(255, 255, 255, 0.4);
  font-family: Arial, Helvetica, sans-serif;
}
.Gallery h2 {
  color: rgba(255, 255, 255, 0.4);
  font-family: Arial, Helvetica, sans-serif;
}
.card {
  box-shadow: 0 0 10px white;
}
.Testimonial .card img {
  width: 125px;
  height: 125px;
  margin: auto;
  border-radius: 50%;
}
.Testimonial .card {
  border: 0;
}
.texttitle {
  padding-top: 300px;
  color: white;
}
.display-4 {
  font-family: Arial, Helvetica, sans-serif;
  font-size: 120px;
  color: rgba(255, 255, 255, 0.4);
  text-shadow: 0 0 10px rgb(0 0 0 / 20%);
  text-align: center;
}
.list-group {
  color: white;
}
.card {
  margin-bottom: 50px;
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
  width: 100%;
  box-shadow: 0 0 10px white;
}
.about-box1 {
  width: 100%;
  text-align: justify;
}
.card-body {
  background-color: white;
}
.aboutrow2 {
  margin: 0;
}
.form-group {
  text-align: left;
}
/* nav {
  background-color: transparent;
} */
#About {
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("../assets/4.jpg");
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  height: 100vh;
  width: 100%;
}
#Gallery {
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("../assets/6.jpg");
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  height: 100%;
  width: 100%;
  padding: 100px;
}
#Testimonial {
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  width: 100%;
  padding: 50px 0 0 0;
}
#Contact {
  background-image: linear-gradient(rgba(0, 0, 0, 0.3), rgba(0, 0, 0, 0.3)),
    url("../assets/7.jpg");
  background-attachment: fixed;
  background-size: cover;
  background-position: center;
  height: 80vh;
  width: 100%;
}
#Footer {
  background-color: black;
}
#Footer p {
  margin: 0;
}
@media (max-width: 580px) {
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

  #About .about-box1 {
    margin-top: 25px;
  }
  #Portfolio {
    padding-top: -150px;
    height: 100%;
  }
  #Gallery {
    width: 100%;
    margin: 0;
    padding-bottom: 20px;
  }
  .display-4 {
    font-size: 50px;
  }

  /* #About .about-box2 .p{

  } */
}
</style>

<template>
  <div class="container-fluid">
    <section class="section1 py-5">
      <h1 class="py-5">
        See why 30,000+ companies <br> across the world use Flock
      </h1>
    </section>
    <section class="section2 py-5 d-flex justify-content-center align-items-center">
      <div id="carouselExample" class="carousel slide">
        <div class="carousel-inner">
          <div class="carousel-item active">
            <div class="card">
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
                <a href="#" class="btn btn-primary">Go somewhere</a>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="card">
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
                <a href="#" class="btn btn-primary">Go somewhere</a>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="card">
              <div class="card-body">
                <h5 class="card-title">Card title</h5>
                <p class="card-text">Some quick example text to build on the card title and make up the bulk of the
                  card's content.</p>
                <a href="#" class="btn btn-primary">Go somewhere</a>
              </div>
            </div>
          </div>
        </div>
        <button class="carousel-control-prev" type="button" data-bs-target="#carouselExample" data-bs-slide="prev">
          <span class="carousel-control-prev-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Previous</span>
        </button>
        <button class="carousel-control-next" type="button" data-bs-target="#carouselExample" data-bs-slide="next">
          <span class="carousel-control-next-icon" aria-hidden="true"></span>
          <span class="visually-hidden">Next</span>
        </button>
      </div>
    </section>
  </div>
</template>

<script>

</script>

<style scoped>
.container-fluid {
  padding: 0;
  margin: 0;
  margin-top: 77px;
  border: 1px solid red;
}

.section1 {
  padding: 0;
  margin: 0;
  text-align: center;
}

.section1 h1 {
  font-size: 60px;
  color: #f5f5f5;
}

.carousel-inner {
  border: 1px solid red;
  width: 70%;
  margin: auto;
}

.carousel{
  width: 70%; 
  border: 1px solid red;
}

.carousel-item .card{
  width: 30em;
  margin: auto;
}

.carousel-control-prev-icon,
.carousel-control-next-icon {
  background-color: black;
}
</style>
<template>
  <div class="carousel">
    <div class="container">
      <div class="row justify-content-center row-content">
        <div class="col-md-8 col-12">
          <div
            id="carouselExampleFade"
            class="carousel slide carousel-fade"
            data-bs-ride="carousel"
          >
            <div class="carousel-inner">
              <div class="carousel-item active">
                <img src="../assets/img(1).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(2).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(3).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(4).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(5).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(6).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(7).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(8).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(9).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(10).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(11).jpg" class="d-block w-100" alt="" />
              </div>
              <div class="carousel-item">
                <img src="../assets/img(12).jpg" class="d-block w-100" alt="" />
              </div>
            </div>
            <a
              class="carousel-control-prev"
              href="#carouselExampleFade"
              role="button"
              data-bs-slide="prev"
            >
              <span
                class="carousel-control-prev-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Previous</span>
            </a>
            <a
              class="carousel-control-next"
              href="#carouselExampleFade"
              role="button"
              data-bs-slide="next"
            >
              <span
                class="carousel-control-next-icon"
                aria-hidden="true"
              ></span>
              <span class="visually-hidden">Next</span>
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { defineComponent } from "@vue/runtime-core";

export default defineComponent({
  name: "Carousel",
  setup() {
    return {
      carousel_message: "",
    };
  },
});
</script>

<style>
h3 {
  font-family: serif,system-ui;
  font-weight: lighter;
}

img {
  margin-top: 1em;
  margin-bottom: 2em;
}

.row-content {
  margin-top:0;
  margin-bottom:0;
}
</style>
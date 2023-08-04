<template>
  <div class="slider">
    <div class="container-custom">
      <div id="carouselExampleIndicators" class="carousel slide mx-auto">
        <ol class="carousel-indicators">
          <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="3"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="4"></li>
          <li data-target="#carouselExampleIndicators" data-slide-to="5"></li>

          <div>
            <button
              class="carousel-control-prev"
              type="button"
              data-target="#carouselExampleIndicators"
              data-slide="prev"
            >
              <span class="sr-only">Previous</span>
            </button>
            <button
              class="carousel-control-next"
              type="button"
              data-target="#carouselExampleIndicators"
              data-slide="next"
            >
              <span class="sr-only">Next</span>
            </button>
          </div>
        </ol>
        <div class="carousel-inner mx-auto">
          <div class="carousel-item active">
            <div class="row w-100 m-0">
              <div class="col-lg-3 col-12 image">
                <img src="../assets/logo-health.svg" alt />
              </div>
              <div class="col-lg col-12 title">
                <h5>
                  “We love the product. It was easy to set up and it was great working with everyone at Pendella. We’re excited to
                  <br />offer this solution to
                  <br />our partners and customers.”
                </h5>
                <p>Jason Hansen, COO - Healthy Business Group (HealthEE)</p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row w-100 m-0">
              <div class="col-lg-3 col-12 image">
                <img src="../assets/logo-health.svg" alt />
              </div>
              <div class="col-lg col-12 title">
                <h5>
                  “We love the product. It was easy to set up and it was great working with everyone at Pendella. We’re excited to
                  <br />offer this solution to
                  <br />our partners and customers.”
                </h5>
                <p>Jason Hansen, COO - Healthy Business Group (HealthEE)</p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row w-100 m-0">
              <div class="col-lg-3 col-12 image">
                <img src="../assets/logo-health.svg" alt />
              </div>
              <div class="col-lg col-12 title">
                <h5>
                  “We love the product. It was easy to set up and it was great working with everyone at Pendella. We’re excited to
                  <br />offer this solution to
                  <br />our partners and customers.”
                </h5>
                <p>Jason Hansen, COO - Healthy Business Group (HealthEE)</p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row w-100 m-0">
              <div class="col-lg-3 col-12 image">
                <img src="../assets/logo-health.svg" alt />
              </div>
              <div class="col-lg col-12 title">
                <h5>
                  “We love the product. It was easy to set up and it was great working with everyone at Pendella. We’re excited to
                  <br />offer this solution to
                  <br />our partners and customers.”
                </h5>
                <p>Jason Hansen, COO - Healthy Business Group (HealthEE)</p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row w-100 m-0">
              <div class="col-lg-3 col-12 image">
                <img src="../assets/logo-health.svg" alt />
              </div>
              <div class="col-lg col-12 title">
                <h5>
                  “We love the product. It was easy to set up and it was great working with everyone at Pendella. We’re excited to
                  <br />offer this solution to
                  <br />our partners and customers.”
                </h5>
                <p>Jason Hansen, COO - Healthy Business Group (HealthEE)</p>
              </div>
            </div>
          </div>
          <div class="carousel-item">
            <div class="row w-100 m-0">
              <div class="col-lg-3 col-12 image">
                <img src="../assets/logo-health.svg" alt />
              </div>
              <div class="col-lg col-12 title">
                <h5>
                  “We love the product. It was easy to set up and it was great working with everyone at Pendella. We’re excited to
                  <br />offer this solution to
                  <br />our partners and customers.”
                </h5>
                <p>Jason Hansen, COO - Healthy Business Group (HealthEE)</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "SliderView",
  props: {
    msg: String
  }
};
</script>
<style lang="scss">
@import "../assets/styles.scss";
.slider {
  padding: 96px 0;
}

button.carousel-control-prev {
  text-align: right;
  width: 32px !important;
  height: 32px !important;
  border-radius: 50% !important;
  left: 90% !important;
  background: url("../assets/prev.png") !important;
  position: absolute;
  transform: scaleX(-1);
  border: none;
  opacity: 1;
  top: 32px !important;
}
.carousel-item {
  & h5 {
    color: $colorBtn-bg;
    width: 705px;
    font-family: Inter;
    font-size: 20px;
    font-style: normal;
    font-weight: 600;
    line-height: 26px;
    margin-bottom: 20px;
    & > br:first-child {
      display: none;
    }
    & > br:last-child {
      display: block;
    }
  }
  & .title {
    padding: 81px 0;
  }
  & .image {
    padding: 98px 66px 44.89px 90px;
    & img {
      width: 109px;
      height: 84.11px;
    }
  }
}
button.carousel-control-next {
  text-align: right;
  width: 32px !important;
  height: 32px !important;
  border-radius: 50% !important;
  background: url("../assets/prev.png") !important;
  position: absolute;
  border: none;
  opacity: 1;
  right: 32px !important;

  top: 32px !important;
}
.carousel {
  width: 1120px !important;
}
.carousel-inner {
  height: 281px;
  background-color: $slider-bg;
  z-index: 1;
  border-radius: 32px;
  width: 1120px !important;
  margin: 0 auto;
}
.carousel-indicators {
  width: 1120px !important;
  justify-content: flex-start !important;
  margin: 0 !important;
  padding: 32px !important;
}
.carousel-indicators li {
  width: 12px !important;
  height: 12px !important;
  background-color: $trusted-color !important;
  border-radius: 50%;
  opacity: 1 !important;
  z-index: 1 !important;
  margin-right: 5px !important;
}
.carousel-indicators .active {
  background-color: $white !important;
}
@media screen and (min-width: 320px) and (max-width: 767px) {
  .slider {
    padding: 60px 0;
  }
  .carousel-indicators {
    width: 100% !important;
  }
  .carousel-inner {
    height: 438px !important;

    width: 335px !important;
  }
  .carousel {
    width: 100% !important;
  }
  .carousel-item {
    & .image {
      padding: 0;
      display: flex;
      justify-content: center;
      margin: 0 auto;
      margin-top: 32px;
    }
    & .title {
      padding: 0 20px;
      margin: 24px 0;
    }
    & h5 {
      width: 100%;
      & > br:first-child {
        display: block;
      }
      & > br:last-child {
        display: none;
      }
    }
  }
  button.carousel-control-prev {
    left: 68% !important;
  }
}
</style>
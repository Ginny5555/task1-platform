<template>
  <div class="hello">
    <div class="main">
      <div class="container-custom">
        <div class="navigation">
          <nav class="navbar navbar-expand-lg">
            <button
              class="navbar-toggler"
              type="button"
              data-toggle="collapse"
              data-target="#navbarScroll"
              aria-controls="navbarScroll"
              aria-label="Toggle navigation"
              :aria-expanded="isNavbarCollapsed"
              @click="toggleNavbarCollapse"
              :class="[navbarClass]"
            >
              <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarScroll">
              <ul
                class="navbar-nav mr-auto my-2 my-lg-0 navbar-nav-scroll d-flex justify-content-end w-100"
              >
                <li class="nav-item dropdown d-lg-flex d-none align-items-center">
                  <a
                    class="nav-link dropdown-toggle"
                    href="#"
                    role="button"
                    data-toggle="dropdown"
                    aria-expanded="false"
                  >Solutions</a>
                  <ul class="dropdown-menu">
                    <li>
                      <a class="dropdown-item" href="#">Action</a>
                    </li>
                    <li>
                      <a class="dropdown-item" href="#">Another action</a>
                    </li>
                    <li>
                      <hr class="dropdown-divider" />
                    </li>
                    <li>
                      <a class="dropdown-item" href="#">Something else here</a>
                    </li>
                  </ul>
                </li>
                <li class="nav-item active d-flex align-items-center">
                  <a class="nav-link" href="#">
                    Company
                    <span class="sr-only">(current)</span>
                  </a>
                </li>
                <li class="nav-item d-flex align-items-center">
                  <a class="nav-link" href="#">Newsroom</a>
                </li>

                <li class="nav-item d-flex align-items-center">
                  <a class="nav-link">Careers</a>
                </li>
                <li class="nav-item contact-us d-flex align-items-center">
                  <a class="nav-link">Contact us</a>
                </li>
                <li class="nav-item partner d-flex align-items-center">
                  <a class="nav-link">Partner with us</a>
                </li>
              </ul>
            </div>
          </nav>
        </div>
        <div
          class="preview row d-flex justify-content-lg-end justify-content-center flex-direction-lg-row flex-direction-column"
        >
          <div class="preview-title mx-auto">
            <h2>
              White-labeled embedded insurance platform for
              <span>[verticals]</span>
            </h2>
            <p>
              Effortlessly offer individual life and disability
              insurance to employees, entirely online. Zero upkeep.
              No monthly fees.
            </p>
            <div class="preview-img d-lg-none d-flex justify-content-center">
              <img src="../assets/main-mob.svg" alt />
            </div>
            <div class="preview-title__button">
              <button>Partner with us</button>
              <div class="demo d-flex align-items-center">
                <span>
                  <img src="../assets/demo.svg" class="d-flex" alt />
                </span>Interactive Demo
              </div>
            </div>
          </div>
          <div class="preview-img d-none d-lg-block">
            <img src="../assets/main1.svg" alt />
          </div>
        </div>
      </div>
    </div>
    <div class="trusted">
      <div class="container-custom">
        <div class="trusted-partners d-flex justify-content-center mx-auto flex-lg-row flex-column">
          <div class="trusted-partners__title">
            <p>Trusted by:</p>
          </div>
          <div class="trusted-partners__logo">
            <img class="p1" src="../assets/Group.svg" alt />
            <img class="p2" src="../assets/sbli_logo.svg" alt />
            <img class="p3" src="../assets/havenlife.svg" alt />
            <img class="p4" src="../assets/logo.svg" alt />
            <img class="p5" src="../assets/afiac.svg" alt />
          </div>
        </div>
      </div>
    </div>
    <div class="easy">
      <div class="container-custom">
        <div class="easy-title text-center mx-auto">
          <h2>
            Life insurance the way it
            <br />should be:
            <span>Easy.</span>
          </h2>
          <p>Bring important financial protection with individual life and disability insurance from top-rated carriers. Policies delivered in under 10 minutes. The process is 100% online and requires no RFP process, no payroll deductions, and no administration.</p>
        </div>
        <div class="easy-blocks">
          <div class="easy-blocks__purpl">
            <div class="row d-flex justify-content-between m-0">
              <div
                class="title col-lg-5 col-12 d-flex flex-column justify-content-center text-lg-left text-center"
              >
                <h3>Intelligent field underwriting</h3>
                <p>Gone are the days of tedious house calls to determine which products are best for your clients. Pendella’s recommendation engine can accurately place users with products they’re most likely to be approved for and best fit their needs.</p>
              </div>
              <div
                class="image col-lg-5 col-12 text-lg-right d-flex justify-content-end text-center"
              >
                <img src="../assets/1.svg" class="w-100 d-lg-block d-none" alt />
                <img src="../assets/1t.svg" class="d-lg-none d-block mx-auto" alt />
              </div>
            </div>
          </div>
          <div class="easy-blocks__blue">
            <div class="row d-flex justify-content-between m-0">
              <div class="image col-lg-5 col-12 d-lg-flex d-none justify-content-start">
                <img src="../assets/2.svg" class="w-100" alt />
              </div>
              <div class="title col-lg-6 col-12 d-flex justify-content-end">
                <div class="d-flex flex-column justify-content-center text-lg-left text-center">
                  <h3>Groundbreaking products from trusted carriers</h3>
                  <p>The traditional term life product is no longer the only option for those looking for long-term protection. We offer products that can pay out monthly, increase in coverage without additional underwriting, and provide a financial lifeline to families, closing the gap group life policies leave behind.</p>
                </div>
              </div>
              <div class="image col-lg-5 col-12 d-lg-none d-block text-lg-left text-center">
                <img src="../assets/2t.svg" class="w-100 mx-auto" alt />
              </div>
            </div>
          </div>
          <div class="easy-blocks__yellow">
            <div class="row d-flex justify-content-between m-0">
              <div
                class="title col-lg-5 col-12 d-flex flex-column justify-content-center text-lg-left text-center"
              >
                <h3>
                  Marketing made
                  (super) easy
                </h3>
                <p>Our agile marketing team works with you to develop tailor-made marketing assets to promote individual life and disability insurance and activate your audience.</p>
              </div>
              <div class="image col-lg-5 col-12 text-right d-flex justify-content-end">
                <img src="../assets/3.svg" class="w-100 d-none d-lg-block" alt />
                <img src="../assets/3t.svg" class="d-lg-none d-block mx-auto" alt />
              </div>
            </div>
          </div>
          <div class="easy-blocks__last d-lg-block d-none">
            <div class="row d-flex justify-content-between m-0">
              <div class="image col-lg-5 col-12 d-flex justify-content-start">
                <img src="../assets/4.svg" class="w-100" alt />
              </div>
              <div class="title col-lg-6 col-12 d-flex justify-content-end">
                <div class="d-flex flex-column justify-content-center">
                  <h3>
                    Coming soon:
                    <br />Big data header
                  </h3>
                  <p>The traditional term life product is no longer the only option for those looking for long-term protection. We offer products that can pay out monthly, increase in coverage without additional underwriting, and provide a financial lifeline to families, closing the gap group life policies leave behind.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="benefits">
      <div class="container-custom">
        <div class="benefits-title text-center mx-auto">
          <h3>Who is this for?</h3>
          <p>
            Our turnkey platform is live in less than a week and seamlessly integrated into your existing benefits strategy, uniquely
            <br />designed to help your business grow.
          </p>
        </div>
        <div class="benefits-cards">
          <div class="row m-0 w-100 benefits-cards__top">
            <div class="col-lg col-12 card">
              <div class="row m-0 w-100">
                <div class="col-lg-2 col-12">
                  <img class="d-none d-lg-block" src="../assets/peo.svg" alt />
                  <img class="d-lg-none d-block mx-auto" src="../assets/gr1.svg" alt />
                </div>
                <div class="col-lg-7 col-12 card-text text-center text-lg-left">
                  <h4>PEOs</h4>
                  <p>Fully whitelabeled to your brand, complementing your other benefits.</p>
                </div>
              </div>
            </div>
            <div class="col-lg col-12 card">
              <div class="row m-0 w-100">
                <div class="col-lg-2 col-12">
                  <img class="d-none d-lg-block" src="../assets/enrollment.svg" alt />
                  <img class="d-lg-none d-block mx-auto" src="../assets/gr2.svg" alt />
                </div>
                <div class="col-lg-7 col-12 card-text text-center text-lg-left">
                  <h4>Enrollment Firms</h4>
                  <p>Effortless for you, your brokers, and clients.</p>
                </div>
              </div>
            </div>
          </div>
          <div class="row m-0 w-100">
            <div class="col-lg col-12 card">
              <div class="row m-0 w-100">
                <div class="col-lg-2 col-12">
                  <img class="d-none d-lg-block" src="../assets/employers.svg" alt />
                  <img class="d-lg-none d-block mx-auto" src="../assets/gr3.svg" alt />
                </div>
                <div class="col-lg-7 col-12 card-text text-center text-lg-left">
                  <h4>Employers</h4>
                  <p>
                    No administrative costs, just a
                    <br />powerful new benefit for your employees.
                  </p>
                </div>
              </div>
            </div>
            <div class="col card">
              <div class="row m-0 w-100">
                <div class="col-lg-2 col-12">
                  <img class="d-none d-lg-block" src="../assets/brokers.svg" alt />
                  <img class="d-lg-none d-block mx-auto" src="../assets/gr4.svg" alt />
                </div>
                <div class="col-lg-7 col-12 card-text text-center text-lg-left">
                  <h4>Brokers</h4>
                  <p>Easy new revenue with no upkeep required, 365 days/year.</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="fingertips">
      <div class="container-custom">
        <div class="fingertips-title text-center mx-auto">
          <h3>Convenient benefits at their fingertips</h3>
          <p
            class="mx-auto"
          >Powered by AI and big data, our fully digital engine serves policy options to employees based on their unique insurance needs. Consumers get coverage in less than 10 minutes in just 3 easy steps, delivering a seamless experience from start to finish:</p>
        </div>
        <div class="fingertips-display mx-auto">
          <div
            class="row fingertips-display__mob d-flex w-100 mx-auto justify-content-lg-between justify-content-center"
          >
            <div
              class="col-lg-3 col-12 col-sm-12 d-flex justify-content-center align-items-center flex-column text-center"
            >
              <h5 class="step-1">Step 1</h5>
              <h5>
                Answer a few questions
                about yourself.
              </h5>
              <img src="../assets/group1.svg" alt />
            </div>
            <div
              class="col-lg-3 col-12 col-sm-12 d-flex justify-content-center align-items-center flex-column text-center"
            >
              <h5 class="step-2">Step 2</h5>
              <h5>
                Receive a personalized
                coverage recommendation.
              </h5>
              <img src="../assets/group2.svg" alt />
            </div>
            <div
              class="col-lg-3 col-12 col-sm-12 d-flex justify-content-center align-items-center flex-column text-center"
            >
              <h5 class="step-3">Step 3</h5>
              <h5>
                Get approved and secure
                your policy same-day.
              </h5>
              <img src="../assets/group3.svg" alt />
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="revenue">
      <div class="container-custom">
        <div class="revenue-title text-center mx-auto">
          <h4>
            <span>Easy new revenue</span> for brokers.
            <span>Powerful new benefits</span> for employers.
            <span>Instant protection</span> for employees.
          </h4>
        </div>
        <div class="revenue-list mx-auto">
          <div class="row w-100 mx-0">
            <div class="col-lg col-12">
              <ul>
                <li>
                  <p>White-labeled to your brand</p>
                </li>
                <li>
                  <p>Advanced reporting and tracking</p>
                </li>
                <li>
                  <p>Lead nurturing included</p>
                </li>
                <li>
                  <p>Marketing materials provided</p>
                </li>
              </ul>
            </div>
            <div class="col-lg col-12 second">
              <ul>
                <li>
                  <p>No heavy lifting</p>
                </li>
                <li>
                  <p>No administrative costs</p>
                </li>
                <li>
                  <p>No payroll deductions</p>
                </li>
                <li>
                  <p>No case management</p>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="schedule">
      <div class="container-custom">
        <div
          class="schedule-title mx-auto d-flex justify-content-center flex-column align-items-center text-center"
        >
          <h4>
            See how easy it is to bring employees the important
            financial protection they deserve
          </h4>
          <button>Schedule demo</button>
        </div>
      </div>
    </div>
    <SliderView />
    <div class="footer d-lg-block d-none"></div>
  </div>
</template>

<script>
import SliderView from "@/views/SliderView.vue";
export default {
  name: "MainView",
  components: {
    SliderView
  },
  data() {
    return {
      isNavbarCollapsed: false
    };
  },
  methods: {
    toggleNavbarCollapse() {
      this.isNavbarCollapsed = !this.isNavbarCollapsed;
    }
  },
  computed: {
    navbarClass() {
      return this.isNavbarCollapsed ? "" : "collapsed";
    }
  }
};
</script>

<style scoped lang="scss">
@import "../assets/styles.scss";
.navigation {
  & .navbar {
    padding: 20px 0 16px 0;
  }
  & a.nav-link {
    color: $color-text;
    font-size: 16px;
    font-weight: 600;
    line-height: 20.8px;
    padding: 0;
  }
  & .partner {
    background-color: $colorBtn-bg;
    border-radius: 8px;
    padding: 12px 36px;
    margin-left: 12px;
    & a.nav-link {
      color: $white;
    }
  }
  & ul li {
    margin-right: 12px;
    padding: 10px 12px 9px;
    border-radius: 8px;
    &:hover {
      background-color: $hover-bg;
      cursor: pointer;
    }
  }
}

.preview {
  padding-bottom: 89.21px;
  &-title {
    width: 531px;
    margin-top: 69px;
    margin-right: 40px;

    & p {
      width: 458px;
    }
    &__button {
      display: inline-flex;
      button {
        padding: 12px 28px;
        border-radius: 8px;
        background-color: $colorBtn-bg;
        color: $white;
        border: none;
        cursor: pointer;
        margin-right: 28px;
        line-height: 16px;
      }
      & .demo {
        display: inline-flex;
        font-size: 16px;
        font-style: normal;
        font-weight: 600;
        line-height: 20.8px;
        color: $colorBtn-bg;
      }
      & span {
        margin-right: 8px;
        width: 15px;
        height: 15px;
      }
    }
    & h2 span {
      color: $blue-text;
      font-size: 44px;
      font-weight: 600;
      line-height: 20.8px;
      letter-spacing: -0.88px;
    }
    & p {
      margin-bottom: 48px !important;
    }
  }
  &-img img {
    margin-top: 59.99px;
    width: 632.36px;
    height: 366.79px;
  }
}
.trusted {
  background-color: $bg-partners;
  padding: 51px 0 50px;
  &-partners {
    width: 937px;

    &__title p {
      margin-right: 52px;
      color: $trusted-color;
      text-align: center;

      font-size: 16px;
      font-style: normal;
      font-weight: 600;
      line-height: 20.8px;
    }
    &__logo img {
      margin-right: 52px;
      &:last-child {
        margin: 0;
      }
    }
  }
}
.easy {
  padding-top: 96px;
  &-title {
    width: 937px;
    margin-bottom: 72px;

    & h2 {
      margin-bottom: 28px;
    }
    & span {
      color: $blue-text;
    }
    & p {
      margin-bottom: 0;
    }
  }
  &-blocks {
    & img {
      width: 300px !important;
      height: 300px;
      margin-right: 0;
    }
    &__purpl {
      background-color: $easy-bg-purpl;
      border-radius: 32px;
      margin-bottom: 72px;
      & div.title {
        padding: 101px 0 100px 122px;
        & h3 {
          width: 417px;
          margin-bottom: 24px;
        }
        & p {
          width: 417px;
        }
      }
      & .image {
        padding: 67px 180px 67px 0;
      }
    }
    &__blue {
      background-color: $easy-bg-blue;
      border-radius: 32px;
      margin-bottom: 72px;
      & div.title {
        padding: 90px 97px 90px 0;
        & h3 {
          width: 483px;
          margin-bottom: 24px;
        }
        & p {
          width: 406px;
        }
      }
      & div.image {
        padding: 67px 0 67px 180px;
      }
    }
    &__yellow {
      background-color: $easy-bg-yellow;
      border-radius: 32px;
      margin-bottom: 72px;
      & div.title {
        padding: 111px 0 111px 122px;
        & h3 {
          width: 417px;
          margin-bottom: 24px;
        }
        & p {
          width: 381px;
        }
      }
      & .image {
        padding: 67px 180px 67px 0;
      }
    }
    &__last {
      background-color: $easy-bg-purpl;
      border-radius: 32px;
      margin-bottom: 72px;
      & div.title {
        padding: 90px 97px 90px 0;
        & h3 {
          width: 483px;
          margin-bottom: 24px;
        }
        & p {
          width: 406px;
        }
      }
      & div.image {
        padding: 67px 0 67px 180px;
      }
    }
  }
}
.benefits {
  background-color: $bg-partners;
  padding: 96px 0 96px 0;
  &-title {
    width: 765px;
    margin-bottom: 56px;
    & p {
      & br {
        display: none;
      }
    }
    & h3 {
      margin-bottom: 16px;
    }
  }
  &-cards {
    & .card {
      padding: 50px 0 50px 48px;
      &-text {
        margin-left: 38px;
        & br {
          display: none;
        }
      }
      & img {
        width: 100px;
        height: 100px;
      }
      border-radius: 8px;
      fill: var(--white, #fff);
      filter: drop-shadow(0px 2px 4px rgba(16, 24, 40, 0.06))
        drop-shadow(0px 4px 8px rgba(16, 24, 40, 0.1));
      &:first-child {
        margin-right: 24px;
      }
    }
    &__top {
      margin-bottom: 36px !important;
    }
  }
}
.fingertips {
  padding-top: 96px;
  &-display {
    width: 944px;
    margin-top: 60px;
  }
  & img {
    width: 216px;
    margin-top: 24px;
  }
  & h3 {
    margin-bottom: 24px;
  }
  & p {
    width: 765px;
  }
  & h5 {
    width: 265px;
    margin-bottom: 0;
  }
  & .step-1 {
    color: $finger1;
    margin-bottom: 12px;
  }
  & .step-2 {
    color: $finger2;
    margin-bottom: 12px;
  }
  & .step-3 {
    color: $finger3;
    margin-bottom: 12px;
  }
}
.revenue {
  background-color: $bg-partners;
  padding: 96px 0 96px 0;
  &-title {
    width: 1083px;
    margin-bottom: 60px;
    & h4 {
      margin-bottom: 0;
    }
    & span {
      color: $blue-text;
    }
  }
  &-list {
    width: 910px;
    padding-left: 16px;
    & ul {
      list-style-type: none;
      padding: 0;
    }

    & ul li {
      position: relative;
    }
    & .second ul li {
      margin-left: 48px;
    }
    & ul li p {
      margin-left: 40px;
    }

    & ul li::before {
      content: "";
      position: absolute;
      left: 0;
      top: 50%;
      transform: translateY(-50%);
      width: 24px;
      height: 24px;
      margin-right: 40px;
      background-image: url("../assets/check.svg");
      background-repeat: no-repeat;
      background-position: center;
    }
  }
}

.schedule {
  background-color: $colorBtn-bg;
  padding: 96px 0;
  &-title {
    & h4 {
      color: $white;
      width: 768px;
    }
    & button {
      border-radius: 8px;
      background: $white;
      color: $color-text;
      padding: 12px 28px;
      font-size: 16px;
      margin-top: 28px;
      font-weight: 600;
      line-height: 100%;
      border: none;
      margin-bottom: 0;
    }
  }
}
.footer {
  background-color: $colorBtn-bg;
  height: 619px;
}
@media screen and (min-width: 320px) and (max-width: 767px) {
  .preview {
    padding-bottom: 60px;
    &-img img {
      margin: 40px 0;
      width: 320px;
      height: 208.1px;
    }
    &-title {
      width: 100%;
      margin-top: 60px;
      & p {
        text-align: center;
        width: 100%;
        margin-bottom: 0 !important;
      }
      & h2 {
        text-align: center;
        font-size: 28px;
        font-weight: 600;
        line-height: 36.4px;
        letter-spacing: -0.56px;
        margin-bottom: 24px;
        & span {
          text-align: center;
          font-size: 28px;
          font-weight: 600;
          line-height: 36.4px;
          letter-spacing: -0.56px;
        }
      }

      &__button {
        display: flex;
        flex-direction: column !important;
        margin: 0 auto;
        width: 174px;
        button {
          border-radius: 8px;
          width: 174px;
          margin: 0 auto;
          padding: 12px 28px;
          line-height: 16px;
        }
        & .demo {
          margin-top: 20px;

          margin-top: 20px;
        }
        & span {
          margin-right: 13.26px;
        }
      }
    }
  }
  .easy {
    padding: 60px 0;
    &-title {
      width: 345px;
      margin-bottom: 24px;
      & h2 {
        font-size: 28px;
        line-height: 36.4px;
        letter-spacing: -0.56px;
        margin-bottom: 24px;
      }
      & p {
        word-wrap: break-word;
      }
      & span {
      }
      & p {
      }
    }
    &-blocks {
      & h3 {
        font-size: 28px;

        line-height: 36.4px;
        letter-spacing: -0.56px;
      }
      & p {
        margin-bottom: 24px;
      }
      & img {
        width: 140px !important;
        height: fit-content;
      }
      &__purpl {
        margin-bottom: 24px;
        padding: 40px 20px;
        & div.title {
          padding: 0;
          & h3 {
            width: 305px;
            margin-bottom: 24px;
          }
          & p {
            width: 305px;
            display: flex;
            justify-content: center;
          }
        }
        & .image {
          padding: 0;
        }
      }
      &__blue {
        padding: 0;
        margin-bottom: 24px;
        padding: 40px 20px;
        & div.title {
          padding: 0;
          & h3 {
            width: 305px;
          }
          & p {
            width: 305px;
          }
        }
        & div.image {
          padding: 0;
        }
      }
      &__yellow {
        height: fit-content;
        margin-bottom: 0;
        padding: 40px 20px;
        & div.title {
          padding: 0;
          & h3 {
            width: 305px;
          }
          & p {
            width: 305px;
          }
        }
        & .image {
          padding: 0;
        }
      }
    }
  }
  .benefits {
    padding: 60px 0;
    &-title {
      width: 100%;
      margin-bottom: 24px;
      & h3 {
        font-size: 28px;
        margin-bottom: 24px;
        line-height: 36.4px;
        letter-spacing: -0.56px;
      }
      & p br {
        display: block;
      }
    }
    &-cards {
      &__top {
        margin-bottom: 24px !important;
      }
      & .card {
        padding: 32px 20px;
        filter: none;
        border: none;
        margin-bottom: 24px;

        &:last-child {
          margin-bottom: 0;
        }
        &-text {
          margin: 16px 0 0 0;
          & br {
            display: block;
          }
          &__top {
            margin-bottom: 0;
          }
        }
      }
    }
  }
  .fingertips {
    padding: 60px 0;
    &-title {
      & h3 {
        font-size: 28px;
        line-height: 36.4px;
        letter-spacing: -0.56px;
      }
    }
    & img {
      width: 120px;
    }
    & p {
      width: 100%;
    }
    &-display {
      width: 100%;
      margin-top: 48px;
      &__mob {
        & div:first-child {
          margin-bottom: 48px;
        }
        & div:nth-child(2) {
          margin-bottom: 48px;
        }
        & div:last-child {
          margin-bottom: 0;
        }
      }
    }
  }
  .revenue {
    padding: 60px 0;
    &-title {
      width: 100%;
      margin-bottom: 32px;
      & h4 {
        margin-bottom: 0;
        font-size: 28px;

        line-height: 36.4px;
        letter-spacing: -0.56px;
      }
    }
    &-list {
      width: 100%;
      & .second ul li {
        margin-left: 0;
      }
      & ul {
        margin-bottom: 0;
      }
    }
    & p {
      font-size: 16px;
      line-height: 41.6px;
    }
  }
  .schedule {
    padding: 60px 0;
    &-title {
      & h4 {
        width: 100%;
        font-size: 24px;
        line-height: 31.2px;
        margin-bottom: 0;
      }
    }
    button {
      margin-top: 32px;
      border: none;
    }
  }
  .trusted {
    padding: 60px 0;
    &-partners {
      width: 320px;
      &__title p {
        margin-bottom: 32px;
        margin-right: 0;
      }
      &__logo {
        display: flex;
        flex-flow: wrap;
        justify-content: center;
        & img {
          height: 30px;
          &.p1 {
            margin-right: 32px !important;
            margin-bottom: 32px;
          }
          &.p3 {
            margin-right: 32px !important;
            margin-bottom: 32px;
          }
          &.p2 {
            margin-right: 0;
            margin-bottom: 32px;
          }
          &.p4 {
            margin-right: 0 !important;
            margin-bottom: 32px;
          }
          &.p5 {
            width: 100%;
            height: 30px;
            margin: 0 auto !important;
          }
        }
      }
    }
  }
  button.navbar-toggler span.navbar-toggler-icon {
    background-image: url("../assets/cross.svg");
    width: 16px;
    height: 16px;
    margin: 8px 12px 8px 12px;
  }
  nav.navbar.navbar-expand-lg.collapsed {
    padding: 32px;
  }
  .navbar {
    display: flex;
    justify-content: end;
  }
  button.navbar-toggler {
    padding: 0;
  }
  .navigation .navbar {
    padding: 22px 0;
  }
  button.navbar-toggler.collapsed span.navbar-toggler-icon {
    background-image: url("../assets/menu.svg");
    width: 32px;
    height: 32px;
    margin: 0;
  }
  .navigation a.nav-link {
    font-size: 28px;

    line-height: 36.4px;
    margin-bottom: 24px;
  }
  .partner a.nav-link {
    font-size: 16px;
    margin-bottom: 0;
    line-height: 16px;
  }
  li.nav-item.partner {
    width: 190px;
    margin: 0;
  }
  .navigation ul li {
    padding: 0;
  }
  .navbar-collapse {
    margin-top: 28px;
  }
}

@media screen and (min-width: 1200px) {
}
</style>

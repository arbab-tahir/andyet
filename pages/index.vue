<template>
  <div>
    <div class="backContainer">
      <img
        class="bgImage"
        src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2016/02/2.jpg"
        alt="Background Picture"
      />
      <div class="centered">
        <p>PROBABLY THE BEST CREATIVE SPACE IN THE CITY</p>
        <h1 class="pHeading">CREATIVE SPACE</h1>
        <br />
        <!-- Button trigger modal -->
        <button
          type="button"
          class="btn bookTour"
          data-bs-toggle="modal"
          data-bs-target="#exampleModal"
        >
          BOOK A TOUR
        </button>
      </div>
      <!-- Modal -->
      <div
        class="modal fade"
        id="exampleModal"
        tabindex="-1"
        aria-labelledby="exampleModalLabel"
        aria-hidden="true"
      >
        <div class="modal-dialog">
          <div class="modal-content">
            <div class="modal-header mHeader">
              <h1 class="modal-title fs-5 text-center" id="exampleModalLabel">
                Book A Tour
              </h1>
              <button
                type="button"
                class="btn-close"
                data-bs-dismiss="modal"
                aria-label="Close"
              ></button>
            </div>
            <div class="modal-body">
              <p class="text-black">
                Would you like to see our space before joining? Come and visit
                our conoble space. Please fill out the form and our manager will
                get back asap.
              </p>
              <br />

              <div class="row g-3">
                <div class="col">
                  <input
                    type="text"
                    class="form-control mInput"
                    placeholder="First name"
                    aria-label="First name"
                  />
                </div>
                <div class="col">
                  <input
                    type="text"
                    class="form-control mInput"
                    placeholder="Last name"
                    aria-label="Last name"
                  />
                </div>
              </div>
              <br />
              <div class="row g-3">
                <div class="col">
                  <input
                    type="text"
                    class="form-control mInput"
                    placeholder="Email"
                    aria-label="Email"
                  />
                </div>
                <div class="col">
                  <input
                    type="text"
                    class="form-control mInput"
                    placeholder="Phone"
                    aria-label="Phone"
                  />
                </div>
              </div>
            </div>
            <div class="modal-footer border-0">
              <button
                type="button"
                class="btn w-100 rTB"
                data-bs-dismiss="modal"
              >
                REQUEST TO BOOK
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>

    <Home />
  </div>
</template>

<script>
export default {
  name: "IndexPage",
};
</script>

<style scoped>
.backContainer {
  position: relative;
  text-align: center;
  color: white;
}

.mHeader {
  background-color: #2ebd7f;
}

.mInput {
  border-radius: 0%;
  padding: 10px;
  font-size: 13px;
}

.mInput:focus {
  outline: none !important;
  border-color: #2ebd7f;
  box-shadow: 0 0 1px #2ebd7f;
}

.bookTour {
  background-color: #2ebd7f;
  color: white;
  padding-right: 40px;
  padding-left: 40px;
  padding-top: 10px;
  padding-bottom: 10px;
  border-style: none;
  border-radius: 0;
}

.rTB {
  background-color: #2ebd7f;
  color: white;
  border-style: none;
  border-radius: 0;
  padding-right: 20px;
  padding-left: 20px;
  padding-top: 10px;
  padding-bottom: 10px;
}
.centered {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  /* font-size: 88px; */
  /* letter-spacing: 0.0625em; */
}

.centered p {
  font-size: 18px;
  letter-spacing: 0.0625em;
}

.pHeading {
  font-size: 88px;
  letter-spacing: 0.0625em;
  width: max-content;
}
.bgImage {
  background-image: url(https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2016/02/2.jpg);
  background-position: center center;
  background-repeat: no-repeat;
  width: 100%;
  height: 100vh;
  background-size: cover;
}

@media only screen and (max-width: 740px) {
  .pHeading {
    font-size: 75px;
    letter-spacing: 0.0625em;
    width: max-content;
  }
}
@media only screen and (max-width: 640px) {
  .pHeading {
    font-size: 70px;
    letter-spacing: 0.0625em;
    width: max-content;
  }
}
@media only screen and (max-width: 600px) {
  .pHeading {
    font-size: 65px;
    letter-spacing: 0.0625em;
    width: max-content;
  }
}
@media only screen and (max-width: 550px) {
  .pHeading {
    font-size: 55px;
    letter-spacing: 0.0625em;
    width: max-content;
  }
}
@media only screen and (max-width: 470px) {
  .pHeading {
    font-size: 48px;
    letter-spacing: 0.0625em;
    width: max-content;
  }
}

@media only screen and (max-width: 405px) {
  .pHeading {
    font-size: 38px;
    letter-spacing: 0.0625em;
    width: max-content;
  }
}
</style>

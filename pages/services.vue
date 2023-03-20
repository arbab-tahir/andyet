<template>
  <div>
    <div class="backContainer">
      <img
        class="bgImage"
        src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2017/01/Untitled-1.png"
        alt="Background Picture"
      />
      <div class="centered">
        <h1 class="pHeading">ABOUT US (services)</h1>
        <br />
      </div>
    </div>

    <div class="container contain2 p-5">
      <div class="row">
        <div class="col-sm-5 col-md-6">
          <div class="row">
            <div class="col">
              <img
                class="w-100"
                src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2017/01/top.png"
                alt="..."
              />
            </div>
          </div>

          <div class="row mt-4">
            <div class="col">
              <img
                class="w-100"
                src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2017/01/left.png"
                alt="..."
              />
            </div>
            <div class="col">
              <img
                class="w-100"
                src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2017/01/right.png"
                alt="..."
              />
            </div>
          </div>
        </div>
        <div class="col-sm-5 offset-sm-2 col-md-6 offset-md-0">
          <div class="card-body border-0 text-center mt-5">
            <img
              class="logoImg"
              src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2016/02/logo.png"
              alt="ABOUT OUR FRIENDLY COMMUNITY"
            />
            <br /><br />
            <h5 class="card-title cTitle">ABOUT OUR FRIENDLY COMMUNITY</h5>
            <br />
            <div class="cText">
              <p class="card-text">
                Whether it’s working for yourself, or remotely, it’s great to be
                independent. Our purpose is to create an environment that allows
                you to focus on what’s really important, getting your work done
                and meet interesting people. All these in one place!
              </p>
            </div>
            <button type="button" class="btn learnMore">
              JOIN NOW
              <!-- <font-awesome-icon class="aIcon" icon="fa-solid fa-arrow-right" /> -->
            </button>
          </div>
        </div>
      </div>
    </div>

    <div class="container-fluid conatin2 mt-5 mb-5">
      <div class="h2 p-5 text-center">MEET OUR TEAM</div>

      <div class="row row-cols-1 row-cols-md-3 g-4 justify-content-center">
        <div class="col">
          <div class="card border-0 bg-transparent">
            <img
              src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2017/01/Layer-51.png"
              alt="..."
            />
            <div class="card-body text-center">
              <h5 class="card-title">Kathleen May</h5>
              <p class="card-text">Receptionist</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card border-0 bg-transparent">
            <img
              src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2017/01/Layer-49-1.png"
              alt="..."
            />
            <div class="card-body text-center">
              <h5 class="card-title">Ronald Fisher</h5>
              <p class="card-text">CEO</p>
            </div>
          </div>
        </div>
        <div class="col">
          <div class="card border-0 bg-transparent">
            <img
              src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2017/01/cropped-Layer-50-1.png"
              alt="..."
            />
            <div class="card-body text-center">
              <h5 class="card-title">Jessica Lynch</h5>
              <p class="card-text">Manager</p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "services",
};
</script>

<style scoped>
.conatin2 {
  background-color: #f9f9f9;
}
.aIcon {
  padding-left: 10px;
}

.bTitle {
  font-size: 26px;
  font-weight: bold;
  padding-top: 80px;
  padding-bottom: 90px;
  margin-bottom: 25px;
  letter-spacing: 0.0625em;
}

.price {
  color: #2ebd7f;
  font-size: 30px;
  font-family: "Courier New", Courier, monospace;
}

.period {
  color: #2ebd7f;
}
.learnMore {
  margin-top: 30px;
  background-color: #2ebd7f;
  color: white;
  border-radius: 0;
  padding-top: 10px;
  padding-bottom: 10px;
  padding-right: 40px;
  padding-left: 40px;
}
.contain {
  background-color: #f9f9f9;
}

.cTitle {
  letter-spacing: 0.0625em;
  font-size: 25px;
}
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
  padding-right: 20px;
  padding-left: 20px;
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

@media only screen and (max-width: 1025px) {
  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
  }

  .mInput {
    /* width: 370px; */
    margin-left: 80px;
  }
}

@media only screen and (max-width: 913px) {
  /* .cText {
    max-width: 100%;
    margin-left: 0px;
  } */
  .pHeading {
    /* font-size: 75px; */
    letter-spacing: 0.0625em;
    width: 800px;
  }

  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
  }

  .mInput {
    width: 370px;
  }
}

@media only screen and (max-width: 770px) {
  .tCard {
    width: 100%;
  }
  .contain {
    height: 80vh;
  }
  .cText {
    padding-left: 0px;
    padding-right: 0px;
  }

  .pHeading {
    /* font-size: 75px; */
    letter-spacing: 0.0625em;
    width: 700px;
  }

  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
  }

  .mInput {
    width: 370px;
  }
}

@media only screen and (max-width: 740px) {
  .tCard {
    width: 100%;
  }
  .contain {
    height: 80vh;
  }
  .cText {
    padding-left: 0px;
    padding-right: 0px;
  }

  .pHeading {
    font-size: 75px;
    letter-spacing: 0.0625em;
    /* width: max-content; */
  }

  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
  }

  .mInput {
    width: 370px;
  }
}

@media only screen and (max-width: 640px) {
  .tCard {
    width: 100%;
  }
  .contain {
    height: 80vh;
  }
  .cText {
    padding-left: 0px;
    padding-right: 0px;
  }

  .mContent {
    /* width: 100%; */
    height: auto;
  }

  .pHeading {
    font-size: 75px;
    letter-spacing: 0.0625em;
    /* width: max-content; */
  }

  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
  }

  .mInput {
    width: 370px;
  }
}
@media only screen and (max-width: 600px) {
  .tCard {
    width: 100%;
  }
  .contain {
    height: 80vh;
  }
  .cText {
    padding-left: 0px;
    padding-right: 0px;
  }

  .mContent {
    /* width: 100%; */
    height: auto;
  }
  .pHeading {
    font-size: 75px;
    letter-spacing: 0.0625em;
    /* width: max-content; */
  }

  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
    padding-top: 10px;
    padding-bottom: 10px;
  }

  .mInput {
    width: 370px;
    padding-top: 10px;
    padding-bottom: 10px;
  }
}
@media only screen and (max-width: 550px) {
  .tCard {
    width: 100%;
  }
  .contain {
    height: 80vh;
  }
  .cText {
    margin-left: 0px;
  }

  .mContent {
    /* width: 100%; */
    height: auto;
  }
  .pHeading {
    font-size: 55px;
    letter-spacing: 0.0625em;
    width: 330px;
  }

  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
    padding-top: 10px;
    padding-bottom: 10px;
  }

  .mInput {
    width: 500px;
    padding-top: 10px;
    padding-bottom: 10px;
  }
}
@media only screen and (max-width: 470px) {
  .tCard {
    width: 100%;
  }
  .contain {
    height: 80vh;
  }
  .cText {
    padding-left: 0px;
    padding-right: 0px;
  }

  .mContent {
    /* width: 100%; */
    height: auto;
  }
  .pHeading {
    font-size: 40px;
    letter-spacing: 0.0625em;
    width: 300px;
  }

  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
    padding-top: 10px;
    padding-bottom: 10px;
  }

  .mInput {
    width: 370px;
    padding-top: 10px;
    padding-bottom: 10px;
  }
}

@media only screen and (max-width: 405px) {
  .tCard {
    width: 100%;
  }
  .contain {
    height: 80vh;
  }
  .cText {
    padding-left: 0px;
    padding-right: 0px;
  }

  .mContent {
    /* width: 100%; */
    height: auto;
  }
  .pHeading {
    font-size: 35px;
    letter-spacing: 0.0625em;
    width: 290px;
  }

  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
    padding-top: 10px;
    padding-bottom: 10px;
  }

  .mInput {
    width: 350px;
    padding-top: 10px;
    padding-bottom: 10px;
  }
}

@media only screen and (max-width: 376px) {
  .tCard {
    width: 100%;
  }
  .contain {
    height: 80vh;
  }
  .subRow {
    margin-left: 0px;
  }

  .subscribe {
    width: 100%;
    padding-top: 10px;
    padding-bottom: 10px;
  }

  .mInput {
    width: 335px;
    padding-top: 10px;
    padding-bottom: 10px;
  }
}
</style>

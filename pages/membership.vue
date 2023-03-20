<template>
  <div>
    <div class="backContainer">
      <img
        class="bgImage"
        src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/uploads/2017/01/Layer-45.png"
        alt="Background Picture"
      />
      <div class="centered">
        <h1 class="pHeading">MEMBERSHIP PLANS</h1>
        <br />
      </div>
    </div>

    <div class="container-fluid contain p-5">
      <div class="card mt-5 p-3 border-0 shadow Card">
        <div class="card-body">
          <h5 class="card-title fw-bold cTitle">DROP IN</h5>
          <br />
          <span class="h2 price">$50</span> <i class="period">/1 month</i>
          <br />
          <br />
          <p class="card-text">
            Drop by Calendarius between 9am-5pm four times each month. Use our
            drop-in area, kitchen and phone booths. Free Coffee & Fast Internet
            & Professional Network.
          </p>
          <button type="button" class="btn learnMore float-end">
            SELECT THIS PLAN
            <font-awesome-icon class="aIcon" icon="fa-solid fa-arrow-right" />
          </button>
        </div>
      </div>

      <div class="card mt-5 p-3 border-0 shadow">
        <div class="card-body">
          <h5 class="card-title fw-bold cTitle">DESK</h5>
          <br />
          <span class="h2 price">$150</span> <i class="period">/1 month</i>
          <br />
          <br />
          <p class="card-text">
            24 / 7 access to Calendarius' drop in table area. Full use of our
            drop-in area, kitchen, conference rooms, and phone booths. Free
            Coffee & Fast Internet & Mail Collection & Professional Network.
            Daily, weekly, and monthly events.
          </p>
          <button type="button" class="btn learnMore float-end">
            SELECT THIS PLAN
            <font-awesome-icon class="aIcon" icon="fa-solid fa-arrow-right" />
          </button>
        </div>
      </div>

      <div class="card mt-5 p-3 border-0 shadow">
        <div class="card-body">
          <h5 class="card-title fw-bold cTitle">DEDICATED</h5>
          <br />
          <span class="h2 price">$300</span> <i class="period">/1 month</i>
          <br />
          <br />
          <p class="card-text">
            24 / 7 Access to Your Own Large Desk. Motorized Sit & Stand Desk.
            Personal File Cabinet with Lock. Access to FUSE's drop in table
            area. Full use of our kitchen, conference rooms, and phone booths.
            Free Coffee & Fast Internet & Mail Collection & Professional
            Network. Daily, weekly, and monthly events.
          </p>
          <button type="button" class="btn learnMore float-end">
            SELECT THIS PLAN
            <font-awesome-icon class="aIcon" icon="fa-solid fa-arrow-right" />
          </button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "membership",
};
</script>

<style scoped>
.aIcon {
  padding-left: 10px;
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
  margin-top: 20px;
  background-color: white;
  color: #2ebd7f;
  border-radius: 0;
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

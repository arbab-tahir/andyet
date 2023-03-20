<template>
  <div>
    <div class="container-fluid pt-5 mt-4 contain">
      <div class="row">
        <div class="col-sm-5 col-md-6 m-0 p-0">
          <div class="mapouter">
            <div class="gmap_canvas">
              <iframe
                width="100%"
                height="100%"
                id="gmap_canvas"
                src="https://maps.google.com/maps?q=Lahore, Arfa&t=&z=15&ie=UTF8&iwloc=&output=embed"
                frameborder="0"
                scrolling="no"
                marginheight="0"
                marginwidth="0"
              ></iframe
              ><a href="https://2yu.co">2yu</a><br /><a
                href="https://embedgooglemap.2yu.co/"
                >html embed google map</a
              >
            </div>
          </div>
        </div>

        <div class="col-sm-5 offset-sm-2 col-md-6 offset-md-0 infoCol">
          <div class="card bg-transparent border-0 text-white">
            <!-- <h5 class="card-header bg-transparent border-0"></h5> -->
            <div class="card-body cBody">
              <h5 class="card-title cTi">COME & VISIT</h5>
              <p class="card-text">
                We really love meeting new people. Step by to say hello!
              </p>
              <hr class="h-5 w-25" />
            </div>
          </div>

          <div class="card bg-transparent border-0 text-white pb-5">
            <!-- <h5 class="card-header bg-transparent border-0"></h5> -->
            <div class="card-body">
              <h5 class="card-title"></h5>
              <div class="row">
                <div class="col-4">
                  <font-awesome-icon
                    class="w-50 locIcon float-end"
                    icon="fa-solid fa-location-dot"
                  />
                </div>
                <div class="col-4">
                  <p class="card-text">
                    55 East 52nd Street <br />
                    21st Floor<br />
                    New York, NY<br />
                    10022
                  </p>
                </div>
              </div>
              <br />
              <div class="row">
                <div class="col-4">
                  <font-awesome-icon
                    class="w-50 locIcon float-end"
                    icon="fa-solid fa-phone"
                  />
                </div>
                <div class="col-4">
                  <p class="card-text">1 (112) 4COWORK</p>
                </div>
              </div>
              <br />
              <div class="row">
                <div class="col-4">
                  <font-awesome-icon
                    class="w-50 locIcon float-end"
                    icon="fa-solid fa-envelope"
                  />
                </div>
                <div class="col-4">
                  <p class="card-text">sales@highseastudio.co</p>
                </div>
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
  name: "location",
};
</script>

<style scoped>
.gmap_canvas {
  overflow: hidden;
  background: none !important;
  height: 100%;
  width: 100%;
}
.mapouter {
  position: relative;
  text-align: right;
  height: 100%;
  width: 100%;
}
.cBody {
  padding-top: 120px;
  padding-left: 50px;
}
.cTi {
  font-size: 35px;
}
.infoCol {
  background-color: #2ebd7f;
}

.locIcon {
  font-size: 30px;
}
</style>

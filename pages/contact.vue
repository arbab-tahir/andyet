<template>
  <div>
    <div class="container mt-5 pt-5 pb-5 text-center contain w-75">
      <div class="modal-dialog">
        <div class="modal-content">
          <i>
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="50"
              height="50"
              viewBox="0 0 36 26"
            >
              <path
                fill="#2ebd7f"
                d="M35.918 2.52c-.205-.895-.816-1.667-1.596-2.114C33.832.162 33.3 0 32.73 0H3.272C2.7 0 2.17.162 1.678.406.86.853.288 1.626.082 2.52.042 2.76 0 3.005 0 3.25v19.5C0 24.537 1.473 26 3.272 26h29.455c1.8 0 3.272-1.463 3.272-3.25V3.25c0-.244-.042-.488-.082-.73zm-5.893.73L18 12.31 5.973 3.25h24.052zm2.704 19.5H3.272V5.322l13.746 10.36c.285.203.653.324.98.324s.695-.12.98-.324l13.75-10.36V22.75z"
              ></path>
            </svg>
          </i>
          <br />
          <div class="modal-header mHeader">
            <h1 class="card-title text-center"></h1>
          </div>
          <br />
          <div class="modal-body">
            <p class="text-black">
              Join our great coworking space and community. Please fill out the
              form and our manager will get back asap.
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
              <textarea
                class="form-control mInput2"
                placeholder="Your Message"
              ></textarea>
            </div>
          </div>
          <br />
          <div class="modal-footer border-0">
            <button type="button" class="btn w-100 rTB" data-bs-dismiss="modal">
              SEND
            </button>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "contact",
};
</script>

<style scoped>
.card-title {
  margin-left: 355px;
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

.mInput2 {
  border-radius: 0%;
  padding: 10px;
  font-size: 13px;
  width: 98.4%;
  margin-left: 8px;
  height: 120px;
}

.mInput2:focus {
  outline: none !important;
  border-color: #2ebd7f;
  box-shadow: 0 0 1px #2ebd7f;
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

@media only screen and (max-width: 770px) {
  .card-title {
    margin-left: 60px;
  }
}

@media only screen and (max-width: 740px) {
  .card-title {
    margin-left: 60px;
  }
}

@media only screen and (max-width: 640px) {
  .card-title {
    margin-left: 60px;
  }
}
@media only screen and (max-width: 600px) {
  .card-title {
    margin-left: 60px;
  }
}
@media only screen and (max-width: 550px) {
  .card-title {
    margin-left: 60px;
  }
  .mInput2 {
    width: 95%;
  }
}
@media only screen and (max-width: 470px) {
  .card-title {
    margin-left: 60px;
  }

  .mInput2 {
    width: 95%;
  }
}

@media only screen and (max-width: 405px) {
  .card-title {
    margin-left: 60px;
  }

  .mInput2 {
    width: 95%;
  }
}

@media only screen and (max-width: 376px) {
  .card-title {
    margin-left: 60px;
  }

  .mInput2 {
    width: 95%;
  }
}
</style>

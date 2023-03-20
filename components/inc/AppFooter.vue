<template>
  <div>
    <!-- Footer -->
    <footer class="bg-dark text-center text-white">
      <!-- Grid container -->
      <div class="container p-4">
        <!-- Section: Social media -->
        <section class="mb-4">
          <!-- Facebook -->
          <a
            class="btn btn-outline-light btn-floating m-3 fLinks facebook"
            href="#!"
            role="button"
          >
            <font-awesome-icon icon="fa-brands fa-facebook-f" />
          </a>

          <!-- Twitter -->
          <a
            class="btn btn-outline-light btn-floating m-3 fLinks facebook"
            href="#!"
            role="button"
            ><font-awesome-icon icon="fa-brands fa-twitter"
          /></a>

          <!-- Instagram -->
          <a
            class="btn btn-outline-light btn-floating m-3 fLinks facebook"
            href="#!"
            role="button"
            ><font-awesome-icon icon="fa-brands fa-instagram"
          /></a>

          <!-- Youtube -->
          <a
            class="btn btn-outline-light btn-floating m-3 fLinks facebook"
            href="#!"
            role="button"
            ><font-awesome-icon icon="fa-brands fa-youtube"
          /></a>

          <!-- Pinterest -->
          <a
            class="btn btn-outline-light btn-floating m-3 fLinks facebook"
            href="#!"
            role="button"
            ><font-awesome-icon icon="fa-brands fa-pinterest"
          /></a>

          <!-- Google+ -->
          <a
            class="btn btn-outline-light btn-floating m-3 fLinks facebook"
            href="#!"
            role="button"
          >
            <font-awesome-icon icon="fa-brands fa-google-plus-g"
          /></a>
        </section>
        <!-- Section: Social media -->

        <hr />

        <!-- Section: Form -->
        <!-- <section class="">
          <form action="">
            <div class="row d-flex justify-content-center">
              <div class="col-auto">
                <p class="pt-2">
                  <strong>Sign up for our newsletter</strong>
                </p>
              </div>

              <div class="col-md-5 col-12">
                <div class="form-outline form-white mb-4">
                  <input
                    type="email"
                    id="form5Example21"
                    class="form-control"
                  />
                  <label class="form-label" for="form5Example21"
                    >Email address</label
                  >
                </div>
              </div>

              <div class="col-auto">
                <button type="submit" class="btn btn-outline-light mb-4">
                  Subscribe
                </button>
              </div>
            </div>
          </form>
        </section> -->
        <!-- Section: Form -->

        <!-- Section: Text -->
        <section class="mb-4">
          <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Sunt
            distinctio earum repellat quaerat voluptatibus placeat nam, commodi
            optio pariatur est quia magnam eum harum corrupti dicta, aliquam
            sequi voluptate quas.
          </p>
        </section>
        <!-- Section: Text -->

        <section class="mb-4">
          <a
            class="btn btn-outline-light btn-floating m-3 fLinks2"
            href="#!"
            role="button"
          >
            Services
          </a>

          <a
            class="btn btn-outline-light btn-floating m-3 fLinks2"
            href="#!"
            role="button"
            >Membership</a
          >

          <a
            class="btn btn-outline-light btn-floating m-3 fLinks3 footerLogo"
            href="#!"
            role="button"
          >
            <img
              class="logoFooter"
              src="https://highseastudio.com/demo/coworking/multiple-pages/wp-content/themes/coworking/images/footerlogo.png"
              alt="Co Noble Space"
            />
          </a>

          <a
            class="btn btn-outline-light btn-floating m-3 fLinks2"
            href="#!"
            role="button"
            >Location</a
          >

          <a
            class="btn btn-outline-light btn-floating m-3 fLinks2"
            href="#!"
            role="button"
            >Contact</a
          >
        </section>
      </div>
      <!-- Grid container -->

      <!-- Copyright -->
      <div
        class="text-center p-3"
        style="background-color: rgba(0, 0, 0, 0.2); font-size: 11px"
      >
        Copyright © 2023.
        <a class="text-white" href="#">Conoble Co.</a>
      </div>
      <!-- Copyright -->
    </footer>
    <!-- Footer -->
  </div>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style scoped>
.fLinks2 {
  font-size: 20px;
  text-transform: uppercase;
  border: none;
  font-weight: bold;
  color: grey;
  letter-spacing: 0.0625em;
}

.logoFooter {
  height: 120px;
  width: 120px;
}

.footerLogo:hover {
  background: transparent;
}

.footerLogo {
  cursor: default;
}

.fLinks3 {
  border: none;
}

.fLinks2:hover {
  color: white;
  background: transparent;
}
.fLinks {
  border-radius: 100%;
  font-size: 30px;
}

.facebook {
  width: 60px;
}
</style>

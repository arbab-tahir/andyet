<template>
  <div>
    <nav class="navbar bg-white fixed-top shadow">
      <div class="container-fluid">
        <NuxtLink class="navbar-brand overflow-hidden navLogo" to="/"
          ><b>CONOBLE CO.</b>
        </NuxtLink>
        <!-- <div
          class="d-flex verticleLine"
          style="height: 50px; margin-right: 1000px"
        >
          <div class="vr"></div>
        </div> -->
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="offcanvas"
          data-bs-target="#offcanvasNavbar"
          aria-controls="offcanvasNavbar"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div
          class="offcanvas offcanvas-end text-bg-dark"
          tabindex="-1"
          id="offcanvasNavbar"
          aria-labelledby="offcanvasNavbarLabel"
        >
          <div class="offcanvas-header">
            <!-- <h5 class="offcanvas-title" id="offcanvasNavbarLabel">Offcanvas</h5> -->
            <button
              type="button"
              class="btn-close btn-close-white"
              data-bs-dismiss="offcanvas"
              aria-label="Close"
            ></button>
          </div>
          <div class="offcanvas-body">
            <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
              <li class="nav-item" data-bs-dismiss="offcanvas">
                <NuxtLink to="/" class="nav-link overflow-hidden"
                  >Home</NuxtLink
                >
              </li>
              <li class="nav-item" data-bs-dismiss="offcanvas">
                <NuxtLink to="/services" class="nav-link overflow-hidden"
                  >Services</NuxtLink
                >
              </li>
              <li class="nav-item" data-bs-dismiss="offcanvas">
                <NuxtLink to="/membership" class="nav-link overflow-hidden"
                  >Membership</NuxtLink
                >
              </li>

              <li class="nav-item" data-bs-dismiss="offcanvas">
                <NuxtLink to="/location" class="nav-link overflow-hidden"
                  >Location</NuxtLink
                >
              </li>

              <li class="nav-item" data-bs-dismiss="offcanvas">
                <NuxtLink to="/contact" class="nav-link overflow-hidden"
                  >Contact</NuxtLink
                >
              </li>

              <!-- <li class="nav-item dropdown">
                <a
                  class="nav-link dropdown-toggle"
                  href="#"
                  role="button"
                  data-bs-toggle="dropdown"
                  aria-expanded="false"
                >
                  Dropdown
                </a>
                <ul class="dropdown-menu">
                  <li><a class="dropdown-item" href="#">Action</a></li>
                  <li><a class="dropdown-item" href="#">Another action</a></li>
                  <li>
                    <hr class="dropdown-divider" />
                  </li>
                  <li>
                    <a class="dropdown-item" href="#">Something else here</a>
                  </li>
                </ul>
              </li> -->
            </ul>
            <!-- <form class="d-flex mt-3" role="search">
              <input
                class="form-control me-2"
                type="search"
                placeholder="Search"
                aria-label="Search"
              />
              <button class="btn btn-outline-success" type="submit">
                Search
              </button>
            </form> -->
          </div>
          <hr class="fPartition" />
          <div class="offcanvas-footer">
            <div
              class="btn-toolbar m-lg-1"
              role="toolbar"
              aria-label="Toolbar with button groups"
            >
              <div class="btn-group me-2" role="group" aria-label="First group">
                <button type="button" class="bg-transparent border-0 fIcon">
                  <font-awesome-icon icon="fa-brands fa-facebook-f" />
                </button>
              </div>

              <div class="btn-group me-2" role="group" aria-label="First group">
                <button type="button" class="bg-transparent border-0 fIcon">
                  <font-awesome-icon icon="fa-brands fa-twitter" />
                </button>
              </div>

              <div class="btn-group me-2" role="group" aria-label="First group">
                <button type="button" class="bg-transparent border-0 fIcon">
                  <font-awesome-icon icon="fa-brands fa-instagram" />
                </button>
              </div>

              <div class="btn-group me-2" role="group" aria-label="First group">
                <button type="button" class="bg-transparent border-0 fIcon">
                  <font-awesome-icon icon="fa-brands fa-youtube" />
                </button>
              </div>

              <div class="btn-group me-2" role="group" aria-label="First group">
                <button type="button" class="bg-transparent border-0 fIcon">
                  <font-awesome-icon icon="fa-brands fa-pinterest" />
                </button>
              </div>

              <div class="btn-group me-2" role="group" aria-label="First group">
                <button type="button" class="bg-transparent border-0 fIcon">
                  <font-awesome-icon icon="fa-brands fa-google-plus-g" />
                </button>
              </div>
            </div>
          </div>
        </div>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "AppHeadedr",
};
</script>

<style scoped>
.offcanvas-footer {
  padding: 1rem 1rem;
}

.navbar {
  min-height: 70px;
  border-bottom: 1px solid white;
}

.navLogo {
  color: rgba(0, 0, 0, 10);
  letter-spacing: 0.0625em;
  font-family: "Gill Sans", "Gill Sans MT", Calibri, "Trebuchet MS", sans-serif;
}

.fIcon {
  color: grey;
}

.fIcon:hover {
  color: white;
}

.nav-link {
  color: grey;
  text-transform: uppercase;
  letter-spacing: 0.0625em;
  font-size: 13px;
}

.nav-link:hover {
  color: white;
}

/* @media only screen and (max-width: 1200px) {
  .verticleLine {
    visibility: hidden;
  }
}
@media only screen and (max-width: 600px) {
  .verticleLine {
    visibility: hidden;
  }
}
@media only screen and (max-width: 425px) {
  .verticleLine {
    visibility: hidden;
  }
} */
</style>

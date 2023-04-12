<template>
  <div>
    <div class="container-fluid footerContainer">
      <footer id="dk-footer" class="dk-footer">
        <div class="p-4 px-4">
            <div class="container fContainer px-5">
              <a class="" href="/">
      <img class="px-3" style="height: 25px;"
      src="data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAxMzcuOTMgMTYyLjU5Ij48cGF0aCBmaWxsPSIjZWEwMDkxIiBkPSJNOTUuMDUgMTA1YTEuNTEgMS41MSAwIDAgMCAyLjMuMDhjMi4wNy0yLjMxIDYuMzgtNy4xMiA4LjQtOS40OSAyLjMtMi43IDcuNjgtOC41OCAxMC43OC0xMi4yOGExLjUxIDEuNTEgMCAwIDEgMi40OS4yOGw5LjA3IDE2LjQ5YTMgMyAwIDAgMS0uMTYgMy4yNnEtMi41OSAzLjUxLTYuMzggNy45MS00LjI3IDUtMTAuMTEgMTEuMzlhMS41OSAxLjU5IDAgMCAwLS4wOSAyTDEzNy41OCAxNTdhMS41MyAxLjUzIDAgMCAxLTEuMTkgMi41aC0yNC44MWEzLjEgMy4xIDAgMCAxLTIuMzgtMS4xM2wtMTMuNjgtMTYuNzVhMS41MSAxLjUxIDAgMCAwLTIuMjUtLjA4cS0yMSAyMS4wNi00My42NCAyMS4wNS0yMC44NyAwLTM1LjM5LTEzLjMzQTQzLjY3IDQzLjY3IDAgMCAxIDAgMTE2LjEzcTAtMjMuNSAyMi41Ny0zOS4wNnM3Ljg2LTUuNDMgMTEuMDgtNy42OWExLjQzIDEuNDMgMCAwIDAgLjE5LTIuMThRMTkuNDIgNTEuMjYgMTkuNDIgMzUuNzlxMC0xNS44NSAxMC4zNy0yNS44MlE0MC4zNyAwIDU3IDBxMTYuMjEgMCAyNi43OCA5LjY2YTMxLjYzIDMxLjYzIDAgMCAxIDEwLjU3IDI0LjQgMzEuMiAzMS4yIDAgMCAxLTUuNzkgMTguNDFRODMuMTIgNjAuMzUgNjkuMiA3MS4yYTEuNTggMS41OCAwIDAgMC0uMjggMi4yek01MCA4Ni42NWExLjQ5IDEuNDkgMCAwIDAtMi0uMjljLTQgMy0xNyAxMi44LTIwIDE2LjIzcS01LjE5IDYuMS01LjE4IDEyLjkyIDAgOS43NiA3LjgyIDE3Ljg5IDguMTMgNy44MyAxNy45MSA3LjgzIDEzLjMxIDAgMzAuNTctMTYuOTVhMS42MSAxLjYxIDAgMCAwIC4xNC0yLjE0em0xNC4zNi0zOS4xMUEzMS4wOCAzMS4wOCAwIDAgMCA2OSA0Mi44YTE0LjIxIDE0LjIxIDAgMCAwIDMtOS4yNCAxMy4xMyAxMy4xMyAwIDAgMC00LjE3LTEwLjA4cS00LjE3LTMuODYtMTEuMTktMy44NmExNS40MiAxNS40MiAwIDAgMC0xMC43NyA0IDEyLjE4IDEyLjE4IDAgMCAwLTQuMzggOS42NnEwIDYuOTEgNS41IDEzLjYzczQuMTkgNS4xMyA2LjE2IDcuNWExLjUyIDEuNTIgMCAwIDAgMi4xMi4yMnoiLz48L3N2Zz4="/>
    </a>
    <NuxtLink class="p-3 text-decoration-none text-black-50" to="/contact">Contact</NuxtLink>
    <NuxtLink class="p-3 text-decoration-none text-black-50" to="/jobs">Jobs</NuxtLink>
    <NuxtLink class="p-3 text-decoration-none text-black-50" to="/privacy">Privacy</NuxtLink>


            </div>
        </div>

</footer>
    </div>
  </div>
</template>

<script>
export default {
  name: "AppFooter",
};
</script>

<style scoped>

.footerContainer{
  background-color: #F7F7F7;
}

@media only screen and (max-width: 405px){
  .fContainer{
   padding-right: 0 !important;
   padding-left: 0 !important;
  }

}


</style>

<template>
  <div>
    <div class="container pb-5">
      <div class="card text-center border-0 mt-5">
  <div class="card-header bg-transparent border-0">
  </div>
  <div class="card-body">
    <h1 class="card-title">We aren’t currently hiring.</h1>
    <p class="card-text centP mt-5">
      But we are always up for meeting new people and chatting about web stuff!
       Definitely <a class="text-decoration-none" href="#">send us an email</a> or reach out on
       <a class="text-decoration-none" href="#">Twitter</a>.
    </p>
  </div>
  <div class="card-footer text-muted bg-transparent border-0">
  </div>
</div>
    </div>
  </div>
</template>

<script>
export default {
  name: "jobs",
};
</script>

<style scoped>

.container{
    margin-bottom: 18px;
  }

.centP{
  max-width: 580px;
  margin: 0 auto;
  color: grey;
  font-size: large;
}

@media only screen and (max-width: 405px){
  .container{
    margin-bottom: 198px;
  }
}

</style>

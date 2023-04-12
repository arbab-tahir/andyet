<template>
  <div>
 <div class="container mt-5">
  <div class="row">

    <div class="col-sm-6">
      <div class="card px-4 border-0">
  <div class="card-header bg-transparent border-0">
  </div>
  <div class="card-body">
    <!-- <h3 class="card-title">What can we do for you?</h3> -->
    <h2 class="card-title"><strong>Get in touch</strong></h2>
    <p class="card-text centP mt-4">
      We’d love to hear what you’re working on and how we might be able to help.
       Shoot us an email at <a href="#" class="text-decoration-none">contact@andyet.com</a>
       or fill out this handy form.
    </p>
  </div>
  <div class="card-footer text-muted bg-transparent border-0">
  </div>
</div>
    </div>

    <div class="col-sm-6">
      <div class="container pb-5 formContainer">
  <form class="w-75 pb-5 contactForm">
  <div class="form-group">
    <label for="formGroupExampleInput"><b>Your Name*</b></label>
    <input type="text" class="form-control shadow-none" id="formGroupExampleInput">
  </div>
  <div class="form-group">
    <label for="formGroupExampleInput2"><b>Your Email Address*</b></label>
    <input type="text" class="form-control shadow-none" id="formGroupExampleInput2">
  </div>
  <div class="form-group">
    <label for="formGroupExampleInput2"><b>Your Company*</b></label>
    <input type="text" class="form-control shadow-none" id="formGroupExampleInput2">
  </div>
  <div class="form-group">
    <label for="formGroupExampleInput2"><b>What are you interested in chatting about?*</b></label>
    <select class="select form-control shadow-none">
  <option value="1">Working with us</option>
  <option value="2">Jobs</option>
  <option value="3">Other</option>
</select>
  </div>
  <div class="form-group">
    <label for="formGroupExampleInput2"><b>How can we help you team?*</b></label>
    <textarea type="text" class="form-control shadow-none" rows="3" id="formGroupExampleInput2"></textarea>
  </div>
  <button type="button" class="btn btn-primary float-right shadow-none px-5">Send</button>
</form>
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

textarea{
  resize: none;
}

select{
  appearance: none;
}

@media only screen and (max-width: 405px){
  .formContainer{
    margin-left: 35px;
  }
}

</style>

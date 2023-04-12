<template>
  <div>
    <div class="container pContainer px-5">
      <div class="card pCard px-5 border-0 mt-5">
  <div class="card-header bg-transparent border-0">
  </div>
  <div class="card-body px-5">
    <h1 class="card-title">Privacy Policy</h1>
    <p class="card-text centP mt-3">
      Our default privacy policy is never to gather, store or sell information about you, or to engage in any other behavior that would compromise your privacy and security in any way.
       By default we do not gather personally identifying information.
    </p>

    <h3 class="card-title mt-5">Anonymous Metrics</h3>
    <p class="card-text centP mt-3">
      We collect anonymous website usage data (with no personally identifying information attached) to improve our sites.
      For example, we measure what pages people are visiting and how long visitors stay on our site. We use Google Analytics for this purpose.
    </p>

    <h3 class="card-title mt-5">Contact Form</h3>
    <p class="card-text centP mt-3">
      Do not submit sensitive information, such as payment information or passwords,
       via our contact form. Information sent via our contact form may be shared amongst our team.
        We will not use your contact information for any purpose,
      including marketing emails, except to contact you regarding your inquiry.
      <br/>
      <br/>
      If you have questions or concerns, you can reach us at <br/>
       <a href="#">support@andyet.com</a>.
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
  name: "privacy",
};
</script>

<style scoped>

.centP{
  max-width: 580px;
  color: grey;
  font-size: large;
}

@media only screen and (max-width: 405px) {

  .pContainer{
    padding-right: 0 !important;
    padding-left: 0 !important;
  }

  .pCard{
    padding-right: 0 !important;
    padding-left: 0 !important;
  }

}
</style>

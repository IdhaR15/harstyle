<template>
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <h1>Contact</h1>
        <address class="text-left">
          Kp.Pagergunung 05/03 <br />
          Kec.Purbaratu <br />
          Taroskeun we pami nyasab mah putra bapak umar hehe
        </address>
        <peta />
      </div>
      <!-- ieu diisian ku component form contact -->
      <FormContact />
    </div>
  </div>
</template>

<script>
import peta from "../components/peta.vue";
import FormContact from "../components/FormContact.vue";
export default {
  components: {
    peta,
    FormContact,
  },
};
</script>

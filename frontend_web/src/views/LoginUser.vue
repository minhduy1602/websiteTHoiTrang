<script>
import FormloginVue from "../components/Formlogin.vue";
import toastsVue from "../components/toasts.vue";
export default {
  components: {
    FormloginVue,
    toastsVue,
  },
};
</script>
<template>
  <toastsVue></toastsVue>
  <div class="bg-img">
    <div class="h-100">
      <div class="container-fluid h-custom">
        <div class="row d-flex justify-content-center align-items-center h-100">
          <div class="col-md-9 col-lg-6 col-xl-5">
            <img
              src="../assets/img/logo_green.png"
              class="img-fluid"
              alt="Sample image"
            />
          </div>
          <div class="col-md-8 col-lg-6 col-xl-4 offset-xl-1">
            <FormloginVue></FormloginVue>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
h1 {
  color: #000;
  font-weight: 500;
}
.bg-img {
  background-image: url(../assets/img/sg-banel.png);
  width: auto;
  height: 800px;
}
</style>

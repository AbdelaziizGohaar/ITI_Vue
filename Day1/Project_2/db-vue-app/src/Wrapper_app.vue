<template>
    <div class="wrapper bg-dark text-light">
      <Header_app />
      <div class="container my-5">
        <div class="row">
          <div class="col-md-4">
            <Link_app msg="click here" />
          </div>
          <div class="col-md-8">
            <Body_app msg="welcome for body" />
          </div>
        </div>
      </div>
      <Footer_app />
    </div>
  </template>

<script>
import Footer_app from './components/Footer_app.vue';
import Header_app from './components/Header_app.vue';
import Body_app from './components/Body_app.vue';
import Link_app from './components/Link_app.vue';

export default {
  name: 'Wrapper_app',
  components: {
    Header_app,
    Body_app,
    Link_app,
    Footer_app
  }
};
</script>

<style scoped>
body {
  background-color: #212529;
  color: #ffffff;
}

.wrapper {
  font-family: 'Arial', sans-serif;
}

.min-vh-100 {
  min-height: 100vh;
}

</style>
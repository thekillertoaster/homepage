<template>
  <div class="container">
    <b-form class="form-signin">
      <h1 class="h3 font-weight-normal">Login</h1>

      <b-form-group id="input-group-1">
        <b-form-input id="input-1" placeholder="Enter email" required type="email"></b-form-input>
      </b-form-group>
      <b-form-group id="input-group-2">
        <b-form-input id="input-2" placeholder="Password" required type="password"></b-form-input>
      </b-form-group>
      <b-form-checkbox value="remember">Remember this device</b-form-checkbox>
      <b-button class="mx-auto loginbutton" type="submit" variant="primary">Login</b-button>

    </b-form>
  </div>
</template>

<script lang="ts">
    import Vue from 'vue'

    export default Vue.extend({})
</script>

<style>
  .container {
    margin: 0;
    padding: 0;
    max-width: 100vw;
    background-color: #f8f8f8;
  }

  .form-signin {
    width: 100%;
    max-width: 330px;
    margin: 0 auto;
    margin-top: 30px;
  }

  .form-signin h1 {
    text-align: center;
  }

  #input-group-1 {
    margin-bottom: 0;
  }

  .loginbutton {
    width: 100%;
    max-width: 175px;
    margin-top: 17px;
  }
</style>

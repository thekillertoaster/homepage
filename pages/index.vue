<template>
  <div class="container">
    <b-container class="introductions">
      <b-jumbotron header="Toaster">
        <p>Software and Developer Operations Engineer</p>
        <b-button to="/contact" variant="primary">Contact Me</b-button>
      </b-jumbotron>
    </b-container>
    <b-container class="projects">
      <b-row>
        <b-col></b-col>
        <b-col>
          <h2>Projects</h2>
        </b-col>
        <b-col></b-col>
      </b-row>
    </b-container>
    <b-card-group class="mx-auto projects-row" deck>
      <b-card
        footer="Last Updated: 2020"
        footer-tag="footer"
        header="Software"
        header-tag="header"
        title="Unnamed Software 1"
      >
        <b-card-text>Some random piece of software</b-card-text>
        <b-button href="#" variant="primary">Download</b-button>
      </b-card>
      <b-card
        footer="Last Updated: 2020"
        footer-tag="footer"
        header="Utility"
        header-tag="header"
        title="ToastedCSGO"
      >
        <b-card-text>A random csgo utility</b-card-text>
        <b-button href="#" variant="primary">Purchase</b-button>
      </b-card>
    </b-card-group>
    <b-card-group class="mx-auto projects-row" deck>
      <b-card
        footer="Last Updated: 2020"
        footer-tag="footer"
        header="Software"
        header-tag="header"
        title="Unnamed Software 1"
      >
        <b-card-text>Some random piece of software</b-card-text>
        <b-button href="#" variant="primary">Download</b-button>
      </b-card>
      <b-card
        footer="Last Updated: 2020"
        footer-tag="footer"
        header="Utility"
        header-tag="header"
        title="ToastedCSGO"
      >
        <b-card-text>A random csgo utility</b-card-text>
        <b-button href="#" variant="primary">Purchase</b-button>
      </b-card>
    </b-card-group>
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
    overflow-x: hidden;
  }

  .introductions {
    text-align: center;
    background-color: #f8f8f8;
  }

  .introductions .jumbotron {
    margin-bottom: 0;
  }

  .projects h2 {
    text-align: center;
    margin-bottom: 25px;
    margin-top: 25px;
  }

  .projects-row {
    max-width: 1000px;
    margin-bottom: 25px;
  }
</style>

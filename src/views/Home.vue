<template>
  <div class="home">
    <div class="bg-image">
      <img
        src="https://mdbootstrap.com/img/new/standard/city/053.jpg"
        class="img-fluid"
        alt="Sample"
      />
      <div class="mask" style="background-color: rgba(0, 0, 0, 0.6)">
        <div class="d-flex justify-content-center align-items-center h-100">
          <p class="text-white display-3">Web Developer</p>
        </div>
      </div>
    </div>
    <br />
    <br />
    <br />
    <h1 class="display-4 text-center">Your Vue.js Course</h1>
    <h5 class="text-center">
      Using TypeScript for the framework, npm for installing updates, vue cli for plugins and dependencies.
    </h5>
    <br />
    <br />
    <br />
    <div class="container">
      <div class="row">
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <i class="fab card-header icon fa-accusoft"></i>
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up the bulk of the
                card's content.
              </p>
              <button type="button" class="btn btn-primary">Button</button>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <i class="fab card-header icon fa-accusoft"></i>
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up the bulk of the
                card's content.
              </p>
              <button type="button" class="btn btn-primary">Button</button>
            </div>
          </div>
        </div>
        <div class="col-md-4">
          <div class="card">
            <div class="card-body">
              <i class="fab card-header icon fa-accusoft"></i>
              <h5 class="card-title">Card title</h5>
              <p class="card-text">
                Some quick example text to build on the card title and make up the bulk of the
                card's content.
              </p>
              <button type="button" class="btn btn-primary">Button</button>
            </div>
          </div>
        </div>
      </div>
    </div>
    <HelloWorld />
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";
import HelloWorld from "@/components/HelloWorld.vue"; // @ is an alias to /src

@Options({
  components: {
    HelloWorld
  }
})
export default class Home extends Vue {}
</script>

<style scoped lang="scss">
    .icon {
        font-size: 2em;
        color: grey;
        opacity: 0.4;
    }
</style>

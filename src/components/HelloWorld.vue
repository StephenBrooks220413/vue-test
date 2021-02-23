<template>
  <div class="container">
    <br />
    <br />
    <br />
    <br />
    <div class="row">
      <div class="col-md-6">
        <img 
          src="https://images.unsplash.com/photo-1502945015378-0e284ca1a5be?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
          alt="img"
          class="img-fluid hover-shadow"
        />
      </div>
      <br />
      <div class="col-md-6">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore 
        magna aliqua. Arcu cursus vitae congue mauris rhoncus aenean vel elit. Sed velit dignissim sodales ut eu. Amet 
        risus nullam eget felis eget nunc lobortis. At urna condimentum mattis pellentesque id nibh tortor. Quis eleifend 
        quam adipiscing vitae proin. Platea dictumst vestibulum rhoncus est pellentesque elit. At in tellus integer feugiat 
        scelerisque. Varius sit amet mattis vulputate. Eget nullam non nisi est sit amet facilisis magna. Tristique et 
        egestas quis ipsum suspendisse ultrices gravida dictum fusce. Nisl nunc mi ipsum faucibus vitae aliquet nec.
      </div>
    </div>
    <br />
    <br />
    <br />
    <div class="row">
      <div class="col-md-6">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore 
        magna aliqua. Arcu cursus vitae congue mauris rhoncus aenean vel elit. Sed velit dignissim sodales ut eu. Amet 
        risus nullam eget felis eget nunc lobortis. At urna condimentum mattis pellentesque id nibh tortor. Quis eleifend 
        quam adipiscing vitae proin. Platea dictumst vestibulum rhoncus est pellentesque elit. At in tellus integer feugiat 
        scelerisque. Varius sit amet mattis vulputate. Eget nullam non nisi est sit amet facilisis magna. Tristique et 
        egestas quis ipsum suspendisse ultrices gravida dictum fusce. Nisl nunc mi ipsum faucibus vitae aliquet nec.
      </div>
      <br />
      <div class="col-md-6">
        <img 
          src="https://images.unsplash.com/photo-1502945015378-0e284ca1a5be?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1050&q=80"
          alt="img"
          class="img-fluid hover-shadow"
        />
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import { Options, Vue } from "vue-class-component";

@Options({
  props: {
    msg: String
  }
})
export default class HelloWorld extends Vue {
  msg!: string;
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped lang="scss">
.icon {
   font-size: 2em;
   color: grey;
   opacity: 0.4;
}
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

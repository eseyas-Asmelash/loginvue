
<template>
  <div class="pt-5">
    <div class="border col-md-2 col-sm-12 m-auto p-5 text-info bg-light pt-5">
      <h2> Sign In </h2>
      <hr />
      <div >
          <label for="emailId">Email Address</label>
          <input v-model="emailId" type="text" id="emailId" name="emailId" required>
      </div>

      <div id="inp">
          <label for="pass">Password</label>
          <input v-model="password" type="password" id="pass" name="pass" minlength="8" required>
      </div>
      <button v-on:click="SignIn" class="btn btn-info mt-4 px-2" type="submit">Sign In</button>
    </div>
  </div>
</template>

<script>

export default {
  name: 'HelloWorld',
  data() {
    return {
      emailId : "",
      password : ""
    }

  },
  methods: {
    signIn() {

    }
  }

}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped> 

</style>

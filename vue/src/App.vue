<template>
    <hello-world />
</template>

<script>
//import { component } from "vue/types/umd";
import HelloWorld from "./components/HelloWorld"

/*import Vue from 'vue'
import msal from 'vue-msal'


 
Vue.use(msal, {
    auth: {
      clientId: '',
      
    }
});

new Vue({

    created() {
        if (!this.$msal.isAuthenticated()) {
            this.$msal.sigIn();
        }
    }
});*/

export default {
    name: "app",
  components: {
    HelloWorld
  }
}

</script>
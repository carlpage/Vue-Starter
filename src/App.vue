<template>
  <div>
    {{name}}
  </div>
</template>

<script>
  import Vue from "vue";

  export default Vue.extend({
    data: function() {
      return {
        name: 'Hello World!',
      }
    },
  });
</script>

<style lang="scss">
body {
    border: 10px solid red;
}
</style>
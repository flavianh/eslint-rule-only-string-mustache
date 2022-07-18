<script>
import Vue from "vue";

export default new Vue({
  data: {},
  computed: {
    flag: function () {
      return
    },

    /**
     * @returns {number}
     */
    totalNumber: function () {
      // TODO: Should show an error
      return 2149;
    },
  }
});
</script>
<template>
  <!-- Objective 1: capture `flag` with eslint and vuejs parser -->
  <span>{{ flag }}</span>
  <!-- Objective 2: capture the return type of the `totalNumber` computed property -->
  <span>Il reste {{ totalNumber }} places.</span>
</template>

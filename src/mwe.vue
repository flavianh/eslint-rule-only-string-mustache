<script>

// Challenge: write ESlint rules to achieve objective 1 then objective 2.

import Vue from "vue";

export default new Vue({
  data: {},
  computed: {
    flag: function () {
      return;
    },

    /**
     * @returns {number}
     */
    // Objective 2: for all mustaches in the template which display a computed property, capture the return type and output an error below if number
    // totalNumber should be underlined in red by eslint.
    totalNumber: function () {
      return 2149;
    },
  }
});
</script>
<template>
  <!-- Objective 1: capture the term `flag` with eslint and vuejs parser below. Flag should be underlined in red by eslint. -->
  <span>{{ flag }}</span>
  <span>Il reste {{ totalNumber }} places.</span>
</template>

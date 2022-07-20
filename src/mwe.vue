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
    // Objective 3: for all mustaches in the template which display a computed property, capture the return type and output an error below if number
    // totalNumber should be underlined in red by eslint.
    totalNumber: function () {
      return 2149;
    },
  }
});
</script>
<template>
  <!-- Objective 1: Install eslint and trigger the rule [vue mustache interpolation spacing](https://eslint.vuejs.org/rules/mustache-interpolation-spacing.html#vue-mustache-interpolation-spacing) -->
  <span>{{flag}}</span>
  <!-- Objective 2: capture the term `flag` with eslint and vuejs parser below. Flag should be underlined in red by eslint. -->
  <span>{{ flag }}</span>
  <span>Remains {{ totalNumber }} places.</span>
</template>

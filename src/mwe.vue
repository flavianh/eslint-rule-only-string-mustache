<template>
  {{ totalNumber }}
</template>

<script>

export default {
  computed: {
    /**
     * @returns {number}
     */ 
    totalNumber: function () {
        // TODO: Should fail
        return 'rty';
    }
  }
}
</script>
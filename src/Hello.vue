<template lang="pug">
  div
    p Hello.vue
    p {{ name }}
</template>
<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return({
      name: 'Hello !!!'
    })
  }
})
</script>
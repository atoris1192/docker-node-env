<template lang="pug">
  div
    p MyApp
    Hello
</template>
<script lang="ts">
import Vue from 'vue';
import  Hello  from './Hello.vue';
export default Vue.extend({
  components: {
    Hello,
  }
})
</script>
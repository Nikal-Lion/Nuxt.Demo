<template>
  <!-- <Tutorial/> -->
  <component :is="componentId" :id="90"></component>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({
  data() {
    return {
      componentId:"World"
    }
  },
  methods: {
    
  },
})
</script>

<template lang="">
  <div>
    <h1>
      Test {{ name }}
    </h1>
  </div>
</template>
<script>
  export default {
    name: "World",
    props: {
      id: {
        type: Number,
        default: 0
      }
    },
    computed: {
      name() {
          return this.id + ' hello'
      },
    },
    data() {
      return {

      }
    },
  }

</script>
<style lang="">

</style>

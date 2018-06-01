<template>
  <component :is="name" class="feather" :class="'feather-'+type"></component>
</template>
<script>
  module.exports = {
    props: ['type'],
    computed: {
      name() {
        return `feather-${this.type}`
      }
    }
  }
</script>
<template lang="pug">
  div
    h1 Inicio
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  middleware:"auth"
})
</script>
<template>
  <div class="phone-component">
    <ContainerLabel label="Phone" />
  </div>
</template>

<script>
import ContainerLabel from './helpers/ContainerLabel'

export default {
  components: {
    ContainerLabel
  }
}
</script>

<style scoped>
.phone-component {
  height: 50px;
}
</style>
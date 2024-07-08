<template>
  <div class="steps-indicator-component">
    <ContainerLabel label="Steps Indicator" />
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

<style>
.steps-indicator-component {
  height: 50px;
}
</style>
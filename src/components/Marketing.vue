<template>
  <div class="marketing-component h-100 w-100">
    <ContainerLabel label="Marketing" />
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
.marketing-component{
  background: linear-gradient(159deg, #FFE6BE 70%, #FFC100 40%)
}
</style>
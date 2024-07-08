<template>
  <div id="app" class="p-4">
    <StepsIndicator class="mb-4 bg-lightgray" />
    <div class="main mb-4">
      <div class="left-column bg-lightgray">
        <FormComponent />
      </div>
      <div class="right-column">
        <Marketing />
      </div>
    </div>
    <Phone class="bg-lightgray" />
  </div>
</template>

<script>
import StepsIndicator from './components/StepsIndicator'
import FormComponent from './components/FormComponent'
import Marketing from './components/Marketing'
import Phone from './components/Phone'
import ContainerLabel from './components/helpers/ContainerLabel'

export default {
  name: 'App',
  components: {
    StepsIndicator,
    FormComponent,
    Marketing,
    Phone,
    ContainerLabel
  }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
  max-width: 1280px;
  margin: auto;
  display: flex;
  flex-direction: column;
  height: calc(100vh - 8px);
}

.main {
  display: flex;
  justify-content: space-around;
  flex-wrap: wrap;
  flex: 1;
}

.left-column {
  flex-basis: 100%;
  margin-bottom: 4px;
}

.right-column {
  flex-basis: 100%;
}

@media only screen and (min-width: 1280px) {
  .left-column {
    flex-basis: 100%;
    margin-bottom: 0px;
    max-width: 700px
  }

  .right-column {
    flex-basis: 100%;
    max-width: 500px
  }
}
</style>

<template>
   <div class="app">
    <div class="container-fliud">
      <div class="row">
        <div class="col-12" >
         <login />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import Login from './components/Login.vue'

export default {
  name: 'App',
  components: {
    Login
  }
}
</script>

<style scoped>
  .app{
    max-width: 100%;
    overflow: hidden;
  }
</style>


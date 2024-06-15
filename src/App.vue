<template>
  <NavbarComponent />
  <div class="container">
    <router-view />
  </div>
</template>

<script>
import NavbarComponent from './components/NavbarComponent'
export default {
  name: 'app',
  components: {
    NavbarComponent,
  },
}
</script>

<style>
* {
  font-family: 'Poppins';
  border-radius: 0px !important;
}
body {
  background-color: #f5f3ef;
}
</style>



<template>
  <div id="app">
    <app-header></app-header>
    <app-sidebar></app-sidebar>
    <app-main></app-main>
</div>
</template>

<script>
  import Header from './components/header/header.vue';
  import Sidebar from './components/sidebar/sidebar.vue';
  import Main from './components/main/main.vue';

export default {
  name: 'app',
  data () {
    return {
      msg: 'Welcome to Your Vue.js App'
    }
  },
  methods: {

  },
  computed: {

  },
  components: {
      AppHeader: Header,
      AppSidebar: Sidebar,
      AppMain: Main

  }
}
</script>

<style lang="scss">
@import "common";
</style>

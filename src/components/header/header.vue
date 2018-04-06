<template>
 <header class="header">
   <div class="container">
    <app-logo></app-logo>
     <app-date></app-date>
   </div>
 </header>
</template>
<script>
  import Logo from '../logo/logo.vue';
  import Date from '../date/date.vue';

  export default {
    name: 'app',
    data () {
      return {
//        msg: 'Welcome to Your Vue.js App'
      }
    },
    methods: {

    },
    computed: {

    },
    components: {
      AppLogo: Logo,
      AppDate: Date
    }
  }
</script>

<style lang="scss">
@import "Header";
</style>

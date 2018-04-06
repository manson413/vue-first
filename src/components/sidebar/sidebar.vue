<template>
  <div class="sidebar">
    <app-avatar></app-avatar>
    <menu>
      <li><a href="#">Приход</a></li>
      <li><a href="#">Группы</a></li>
      <li><a href="#">Продукты</a></li>
      <li><a href="#">Пользователи</a></li>
      <li><a href="#">Настройки</a></li>
    </menu>
  </div>
</template>
<script>
  import Avatar from '../avatar/avatar.vue';
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
      AppAvatar: Avatar
    }
  }
</script>

<style lang="scss">
  @import "Sidebar";
</style>

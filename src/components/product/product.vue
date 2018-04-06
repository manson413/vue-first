<template>
  <div class="product"
       v-bind:key="product.id"
       v-bind:specification="product.specification"
  >

  </div>
</template>
<script>


  export default {
    name: 'app',
    data () {
      return {

      }
    },
    methods: {

    },
    computed: {

    },
    components: {

    }
  }
</script>

<style lang="scss">
  @import "product";
</style>

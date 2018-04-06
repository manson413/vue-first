<template>
<div>
  <div class="week-day">{{showDay}}</div>
  <div class="month-day">{{showDate}}</div>

</div>
</template>
<script>

  export default {
    name: 'app',
    data () {
      return {
          myDate : new Date

      }
    },
    methods: {

    },
    computed: {
      showDay(){
        let days = ['Воскресенье', 'Понедельник', 'Вторник', 'Среда', 'Четверг', 'Пятница', 'Суббота'];
        return days[this.myDate.getDay()];
      },
      showDate(){
        return this.myDate.toLocaleString();
      }
    },
    components: {

    }
  }
</script>

<style lang="scss">
  @import "date";
</style>

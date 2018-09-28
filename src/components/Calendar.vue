<template>
  <vue-event-calendar :events="demoEvents"></vue-event-calendar>
</template>

<script>

export default {
  name: 'Calendar',
  data () {
    return {
      demoEvents: [{
        date: '2016/11/12', // Required
        title: 'Foo' // Required
      }, {
        date: '2016/12/15',
        title: 'Bar',
        desc: 'description',
        customClass: 'disabled highlight' // Custom classes to an calendar cell
      }]
    }
  }
}
</script>

<style lang="css">
</style>

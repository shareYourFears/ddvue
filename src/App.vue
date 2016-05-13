<template>
<div is="othercomponent"></div>
</template>

<script>
import Vue from 'vue'
import othercomponent from './OtherComponent.vue'

export default {
  data () {
    return {
      msg: 'Hello frodm vue-loader!',
      currentView: 'test',
    }
  }
}
</script>

<style>
.message {
  color: blue;
}
</style>
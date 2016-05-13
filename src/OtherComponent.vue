<template>
<div class="message">{{ msg }}</div>
</template>

<script>
import Vue from 'vue'

export default Vue.extend({
  data () {
    return {
      msg: 'component here'
    }
  }
});
</script>

<style>
.message {
  color: blue;
}
</style>
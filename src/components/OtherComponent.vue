<template>
	<div class="message">{{ msg }}</div>
</template>

<script>
	export default {
		data () {
			return {
				msg: 'Other Component'
			}
		}
	}
</script>

<style>
	.message {
		color: red;
	}
</style>
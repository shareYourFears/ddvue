<template>
	<div class="message">{{ msg }}</div>
</template>

<script>
	export default {
		data () {
			return {
				msg: 'Second Component'
			}
		}
	}
</script>

<style>
	.message {
		color: red;
	}
</style>
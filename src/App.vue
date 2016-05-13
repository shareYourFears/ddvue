<template>
<h1>Vue App</h1>
<component :is="currentView"></component>
<div id="example">
	<button v-on:click="setCurrentView('other-component')">Set Other</button>
	<button v-on:click="setCurrentView('second-component')">Set Second</button>
</div>
</template>

<script>
import Vue from 'vue'
import OtherComponent from './components/OtherComponent.vue'
import SecondComponent from './components/SecondComponent.vue'

export default {
	components: {
		OtherComponent,
		SecondComponent
	},
	data () {
		return {
			msg: 'Hello frodm vue-lodfgader!',
			currentView: 'other-component'
		}
	},
	methods: {
		setCurrentView: function (viewName) {
			this.currentView = viewName;
		}
	}
}
</script>

<style>
h1 {
	color: darkred;
}
</style>
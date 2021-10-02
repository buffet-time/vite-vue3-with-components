<script lang="ts">
import { Options, Vue } from 'vue-class-component'
import HelloWorld from './components/HelloWorld.vue'

@Options({
	components: {
		HelloWorld: HelloWorld
	}
})
export default class App extends Vue {}
</script>

<template>
	<HelloWorld />
</template>

<style>
body {
	width: 100%;
	height: 100%;
}
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
}
</style>

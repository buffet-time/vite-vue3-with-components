<script lang="ts">
import { Vue } from 'vue-class-component'

export default class HelloWorld extends Vue {}
</script>

<template>
	<div class="lorem">
		Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
		cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat
		non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
	</div>

	<div class="audio-player">
		<audio
			controls
			src="https://github.com/buffet-time/testMusicFolder/raw/main/distortion.flac"
		>
			Your browser does not support the audio element.
		</audio>
	</div>
</template>

<style scoped>
.lorem {
	margin: auto;
	margin-top: 16px;
	width: 75%;
	justify-content: center;
	align-items: center;
}
.audio-player {
	justify-content: center;
	align-items: center;
	margin: auto;
}
</style>

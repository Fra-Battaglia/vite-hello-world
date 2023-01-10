<script>
import { def } from '@vue/shared';

export default {
	data() {
		return {
			Message: "La mia prima app con Vite!"
		}
	}
}
</script>

<template>
	<h1> {{ Message }} </h1>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Montserrat:wght@600&display=swap');

h1 {
	color: #FFFFFF;
	font-family: 'Montserrat', sans-serif;
	text-align: center;
	margin-bottom: 1em;
}
</style>
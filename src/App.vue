<script>
import AppTitle from './components/AppTitle.vue';
import AppHero from './components/AppHero.vue';
export default {
	components: {
		AppTitle,
		AppHero,
	},
};
</script>

<template>
	<div class="container">
		<AppTitle />
		<AppHero />
	</div>
</template>

<style>
* {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

body {
	background-color: #005960;
}

.container {
	width: 100%;
	max-width: 600px;
	margin: auto;
	display: flex;
	height: 100vh;
	flex-direction: column;
	justify-content: center;
}
</style>
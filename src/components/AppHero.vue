<script>
export default {
	data() {
		return {
			Image: "https://media.tenor.com/o656qFKDzeUAAAAC/rick-astley-never-gonna-give-you-up.gif"
		}
	}
}
</script>

<template><img :src="Image" alt="Rick Astley" /></template>

<style>
img {
	width: 100%;
}
</style>
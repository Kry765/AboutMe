<template>
	<HelloWorld />
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
	name: 'App',
	components: {
		HelloWorld,
	},
}
</script>

<style lang="scss">
*,
*::before,
*::after {
	margin: 0;
	padding: 0;
	box-sizing: border-box;
}

html {
	scroll-behavior: smooth;
}

body {
	font-family: 'Red Hat Display', sans-serif;
	font-size: 16px;
}
</style>

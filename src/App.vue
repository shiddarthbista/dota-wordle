<template>
	<Navbar />
	<Dotadle />
</template>

<script>
// Import global components
import Navbar from "@/components/Navbar.vue";
import Dotadle from "@/components/Dotadle.vue";

export default {
	name: "App",
	components: {
		Navbar,
		Dotadle,
	},
};
</script>


<style lang="scss">
#app {
	font-family: "Helvetica Neue", Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	// Site color
	background: $main-color;
	// Site sizing
	height: 100vh;
	width: 100vw;
}

* {
  // Remove default spacing
	margin: 0;
}

html {
  // Handle background on overscroll
  background: $main-color;
}
</style>
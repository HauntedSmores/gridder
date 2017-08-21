<template>
	<div id="app">
		<grid></grid>
	</div>
</template>

<script>
	import Grid from './components/grid';
	export default {
	  name: 'app',
	  components: {
		  'grid': Grid
	  }
	}
</script>

<style lang="scss">
	@import './assets/scss/global';
</style>

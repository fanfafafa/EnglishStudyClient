<template>
	<div id="app">
		<TopContent/>
	</div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import TopContent from './components/TopContent.vue'

export default {
  name: 'app',
  components: {
	TopContent,
    HelloWorld
	
  }
}
</script>

<style>
#app {
}
</style>

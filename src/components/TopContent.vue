<template>
	<div class="top">
		<span class="title">English Study</span>
		<Button class="button" :size="buttonSize" type="text" shape="circle">ADD</Button>
	</div>
</template>

<script>
	export default {
		name: 'TopContent',
		data () {
			return {
				buttonSize: 'large'
			}
		}
	}
</script>

<style scoped>
	.top {
		height: 50px;
		background-color: #2d8cf0;
		
		color: #ffffff;
		font-family: 'Avenir', Helvetica, Arial, sans-serif;
		-webkit-font-smoothing: antialiased;
		-moz-osx-font-smoothing: grayscale;
	}
	
	.title {
		line-height: 50px;
		font-size: 26px;
		font-weight: bold;
		margin-left: 10px;
	}
	
</style>

<template>
  <div id="app">
		<div class="main">
			<img src="../image/FGC.png" alt="">
			<h2>FGC</h2>
			
		</div>
  </div>
</template>

<script>


export default {
  name: 'App',
  components: {

  }
}
</script>

<style lang="less" scoped>
#app {
	display: flex;
	align-items: center;
	justify-content: center;
	.main{
		margin-top: 6.25rem;
		img{
			width: 6.25rem;
			height: 6.25rem;
		}
		h2{
			text-align: center;
		}
	}
}
</style>

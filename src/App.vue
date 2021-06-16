<template>
	<div id="app">
		@{{user.userName}}
	</div>
</template>

<script>

export default {
  name: 'App',
	data(){
		return {
			user: {
				id: 1,
				userName: '_rudra',
				firstName: 'Ratul Rahman',
				lastName: 'Rudra',
				email: 'ratul.rahman.rrr@gmail.com',
				isAdmin: true
			}
		}
	}
}
</script>

<style>
#app {
	font-family: Avenir, Helvetica, Arial, sans-serif;
	-webkit-font-smoothing: antialiased;
	-moz-osx-font-smoothing: grayscale;
	text-align: center;
	color: #2c3e50;
	margin-top: 60px;
}
</style>

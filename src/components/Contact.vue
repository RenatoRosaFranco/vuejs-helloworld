<template>
	<div class="hello">
	  <blockquote class="jumbotron">
			<h1 :title='msg'>{{ msg }}</h1>
			<p>Welcome to contact page.</p>
		</blockquote>
	</div>
</template>

<style type="text/css">
	
</style>

<script type="text/javascript">
	export default {
		data() {
			return {
				msg: 'Contact'
			}
		}
	}
</script>
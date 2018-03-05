<template>
	<div>{{index}}</div>
</template>

<script>
	export default{
		mounted(){
			console.log('index')
		},
		data(){
			return{
				index:0
			}
		}
	}
</script>
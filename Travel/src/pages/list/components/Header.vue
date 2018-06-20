<template>
	<div class="header">
		<router-link to="/" class="header-left">返回</router-link>
	</div>
</template>

<script>

export default{
	name:"ListHeader"
}

</script>

<style>
.header{
	display: flex;
	align-items: center;
	height: .86rem;
	line-height: .68rem;
	background-color: #00bcd4;
	color: #fff;
}
.header-left{
	width: .64rem;
	text-align: center;
	color: #fff;
}
</style>
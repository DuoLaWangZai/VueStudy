<template>
	<div class="header">
		<div class="header-left">返回</div>
		<div class="header-input">输入城市/景点/游玩名称</div>
		<router-link to="/list" class="header-right">
			选择城市
		</router-link>
	</div>
</template>

<script>
export default {
  name: 'HomeHeader'
}
</script>

<style scoped>
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
}
.header-input{
	flex: 1;
	height: .64rem;
	background-color: #fff;
	border-radius: .1rem;
	margin-left: .12rem;
	color: #666;
	padding-left: .2rem;
}
.header-right{
	width: 1.24rem;
	text-align: center;
	color: #fff;
	text-decoration: none;
}
</style>

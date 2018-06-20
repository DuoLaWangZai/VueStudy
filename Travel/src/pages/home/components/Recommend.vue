<template>
	<div>
		<div class="item-title">猜你喜欢</div>
		<div class="item">
			<div class="item-img">
				<img class="item-img-content" src="http://img1.qunarzz.com/sight/p0/1507/36/ce3d2d6c9ab44d67ae68d940b8781829.water.jpg_200x200_0938a8f2.jpg">
			</div>
			<div class="item-desc">
				<p class="item-desc-title">北京野生动物园</p>
			</div>	
		</div>
		<div class="item">
			<div class="item-img">
				<img class="item-img-content" src="http://img1.qunarzz.com/sight/p0/1507/36/ce3d2d6c9ab44d67ae68d940b8781829.water.jpg_200x200_0938a8f2.jpg">
			</div>
			<div class="item-desc">
				<p class="item-desc-title">北京野生动物园</p>
			</div>	
		</div>	
		<div class="item">
			<div class="item-img">
				<img class="item-img-content" src="http://img1.qunarzz.com/sight/p0/1507/36/ce3d2d6c9ab44d67ae68d940b8781829.water.jpg_200x200_0938a8f2.jpg">
			</div>
			<div class="item-desc">
				<p class="item-desc-title">北京野生动物园</p>
			</div>	
		</div>
		<div class="item">
			<div class="item-img">
				<img class="item-img-content" src="http://img1.qunarzz.com/sight/p0/1507/36/ce3d2d6c9ab44d67ae68d940b8781829.water.jpg_200x200_0938a8f2.jpg">
			</div>
			<div class="item-desc">
				<p class="item-desc-title">北京野生动物园</p>
			</div>	
		</div>
	</div>
</template>

<script>

export default{
	name:"HomeRecommend"
}

</script>

<style scoped>
	.item-title{
		height: .44rem;
		line-height: .44rem;
		background-color: #ddd;
		text-indent: .2rem;
	}
	.item{
		display: flex;
		align-items: center;
		padding:.20rem .10rem;
		border-bottom:.01rem solid #eee;
	}
	.item-img{
		width:1.5rem;
		height:1.5rem;
		overflow: hidden;
		background: red;
		border-radius:.12rem;
	}
	.item-img-content{
		width: 100%;
		height: 100%;
	}
	.item-desc-title{
		margin-left: .20rem;
	}
</style>
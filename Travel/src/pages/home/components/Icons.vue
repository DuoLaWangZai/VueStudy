<template>

	<div class="icons">
		<div class="icon" v-for="item of iconList" :key="item.id">
			<div class="icon-img">
				<img :src="item.imgUrl" class="icon-img-content">
			</div>
			<p class="icon-desc">{{item.desc}}</p>
		</div>
	</div>

</template>

<script>

export default{
	name:"HomeIcons",
	data(){
		return{
			iconList:[
				{
					id:"0001",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1803/95/f3dd6c383aeb3b02.png",	
					desc:"景点门票",	
				},
				{
					id:"0002",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1804/ff/fdf170ee89594b02.png",	
					desc:"必游榜单",	
				},
				{
					id:"0003",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1804/ed/cf572be30fc32f02.png",	
					desc:"Q+精选",	
				},
				{
					id:"0004",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1803/bd/9f7b9b2b60c1502.png",	
					desc:"踏青赏花",	
				},
				{
					id:"0005",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1804/5a/13ceb38dcf262f02.png",	
					desc:"一日游",	
				},
				{
					id:"0006",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1803/76/eb88861d78fb9902.png",	
					desc:"动植物园",	
				},
				{
					id:"0007",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1803/6c/9e54a8540fee0102.png",	
					desc:"故宫",	
				},
				{
					id:"0008",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1803/47/c2b659e048b11602.png",	
					desc:"主题乐园",	
				},
				{
					id:"0009",
					imgUrl:"http://img1.qunarzz.com/piao/fusion/1803/e3/67df61427c8e1302.png",	
					desc:"演出",	
				}

			]
		}
	}
}

</script>

<style scoped>
	.icons{
		width: 100%;
		height: 0;
		padding-bottom: 50%;
		overflow: hidden;
		display: flex;
		flex-wrap: wrap; 
		text-align: center;
	}
	.icon{
		position: relative;
		height: 0;
		width: 25%;
		padding-bottom: 25%;
		overflow: hidden;
	}
	.icon-img{
		position: absolute;
		left: 0;
		top: 0;
		right: 0;
		box-sizing: border-box;
		padding: 0.02rem;
		bottom: 0.44rem;
	}
	.icon-img-content{
		margin: 0;
		height: 100%;
	}
	.icon-desc{
		position: absolute;
		bottom: 0;
		height: 0.44rem;
		line-height: 0.44rem;
		width: 100%;
		color: #333;
	}
</style>
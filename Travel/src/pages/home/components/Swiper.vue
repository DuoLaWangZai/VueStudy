<template>
	<div class="wrapper">
		<swiper :options="swiperOption">
			<swiper-slide v-for="(item,index) of items" :key="item.id">
				<img class="swiper-img" :src="item.imgUrl">	   	
		   	</swiper-slide>
		   	<div class="swiper-pagination"  slot="pagination"></div>
		</swiper>	
	</div>
</template>

<script>
export default {
  name: 'HomeHeader',
  data(){
  	return{
  		items:[
  			{
  				id:"0001",
  				imgUrl:"http://img1.qunarzz.com/piao/fusion/1803/98/0a2e0bd8eb0c0802.png_750x200_0a34d4a8.png"
  			},
  			{
  				id:"0002",
  				imgUrl:"http://img1.qunarzz.com/piao/fusion/1805/13/6332699c44387902.jpg_750x200_b7afa4f8.jpg"
  			}
  		],
  		swiperOption:{
  			pagination:".swiper-pagination"
  		}
  	}
  }
}
</script>

<style scoped>
	.wrapper >>> .swiper-pagination-bullet-active{
		background-color: #fff!important;
	}
	.wrapper{
		overflow: hidden;
		width: 100%;
		height: 0;
		padding-bottom: 26.6667%;
		background-color: #eee;
	}
	.swiper-img{
		width:100%;
	}
</style>

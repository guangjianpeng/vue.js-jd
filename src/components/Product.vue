<template>

	<ul class="product clear">

		<li class="left" v-for="(item,index) in nav" :key="index" >
			<a :href="item.url" >
				<img :src="item.image" />
				<a class="a-a" v-text="item.title"></a>
				<span class="a-a1" v-text="item.title2"></span>
				<a class="a-a2" v-text="item.title3"></a>
			</a>
		</li>

	</ul>

</template>

<script>
	export default {

		data() {
			return {
				nav: [{
						title: '【抢！第二份5折】鲜博汇 小龙虾 香辣麻辣熟食 加热即食 1.8kg 4-6钱 35-50只盒装 麻辣小龙虾',
						title2: '¥ 99999',
						title3: '看相似',
						url: '#',
						image: require("@/assets/product/01.jpg")
					},
					{
						title: '山灵（SHANLING） EL1平衡线升级线古河单晶铜mmcx插针接口搭配ME500耳机或ME100 EL1-25B（2.5平衡线）',
						title2: '¥ 99999',
						title3: '看相似',
						url: '#',
						image: require("@/assets/product/02.jpg")
					},
					{
						title: '山灵（SHANLING） EL1平衡线升级线古河单晶铜mmcx插针接口搭配ME500耳机或ME100 EL1-25B（2.5平衡线）',
						title2: '¥ 99999',
						title3: '看相似',
						url: '#',
						image: require("@/assets/product/03.jpg")
					},
					{
						title: '山灵（SHANLING） EL1平衡线升级线古河单晶铜mmcx插针接口搭配ME500耳机或ME100 EL1-25B（2.5平衡线）',
						title2: '¥ 99999',
						title3: '看相似',
						url: '#',
						image: require("@/assets/product/04.jpg")
					},
					{
						title: '山灵（SHANLING） EL1平衡线升级线古河单晶铜mmcx插针接口搭配ME500耳机或ME100 EL1-25B（2.5平衡线）',
						title2: '¥ 99999',
						title3: '看相似',
						url: '#',
						image: require("@/assets/product/05.jpg")
					},
					{
						title: '山灵（SHANLING） EL1平衡线升级线古河单晶铜mmcx插针接口搭配ME500耳机或ME100 EL1-25B（2.5平衡线）',
						title2: '¥ 99999',
						title3: '看相似',
						url: '#',
						image: require("@/assets/product/06.jpg")
					}
				]
			};
		}

	}
</script>

<style lang="less" scoped='scoped'>
	
	.product{

		text-align: center;
		background-color:#F0F2F5;
		padding-bottom: 0.2rem;
		li{
			background-color: white;
			float: left;
			margin: 1%;
			width: 48%;
			box-sizing: border-box;
			padding-bottom: 4px;
			position: relative;
			
		  }
		
		img{
			width:100%;
			height: auto;
		}
		

		
		p{
			margin: 0.12rem 0 0;
			font-size: 0.24rem;
			color: #666;
		}
		.a-a{
			    display:block;
			    box-sizing: border-box;
				height: 31px;
				font-size: 13px;
				overflow: hidden;
				text-overflow: ellipsis;
				display: -webkit-box;
				-webkit-line-clamp: 2;
				-webkit-box-orient: vertical;
				word-break: break-word;
				color: #232326;
				margin-top: 5px;
				line-height: 16px;
				padding: 0 4px;
		}
		.a-a1{
			float: left;
            color: #f23030;
			display: inline-block;
			padding: 0 5px 0 4px;
			position: relative;
			top: 1px;
			height: 0.5rem;
			line-height: 0.5rem;
			text-align: center;
			margin-top: 0.1rem;
		}
		.a-a2{
			float: right;;
			border:1px solid #E7E7E7;
			width: 1rem;
			height: 0.5rem;
			text-align: center;
			line-height: 0.5rem;
			margin-top: 0.1rem;
			font-size: 0.26rem;
		}
		
	}

</style>
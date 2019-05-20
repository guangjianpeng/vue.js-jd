<template>
  <div id="app">
    <router-view/>
  </div>
</template>

<style lang="less">
	html{
		font-size: calc(100vw/7.5); 
	}
	
	body{
		margin: 0 ;
    background: #fff;
    font-size: 14px;
    font-family: -apple-system,Helvetica,sans-serif;
    line-height: 1.5;
    color: #666;
	}
	
	a{
		text-decoration: none;
		color: #333;
	}
	ul{
		margin: 0;
		padding: 0;
	}
	
	ul li{
		list-style: none;
	}
	
	img{
		border: 0 none;
		vertical-align: top;
	}
	.left{
		float: left;
	}
	
	.right{
		float: right;
	}
	
	.clear{
		display: block;
   content: "";
   clear: both;
	}
	
	.flex{
		display: flex;
	}
	
	.flex-item{
		flex:1;
	}
</style>

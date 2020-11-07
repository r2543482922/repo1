<template>
	<view>
		<view class="block1">
			<view class="block"></view>
			<view class="block2">
			<image class="picture" src="../../static/icon-mx@3x.png"></image>
			<view class="font1">收入明细</view>
			<image src="../../static/icon-right@3x.png" class="picture1" @click="touch1()"></image>
			</view>
			<view class="block"></view>
			<view class="block2">
			<image class="picture" src="../../static/icon-tx@3x.png"></image>
			<view class="font1">提现记录</view>
			<image src="../../static/icon-right@3x.png" class="picture1" @click="touch2()"></image>
			</view>
			<view class="block"></view>
			<view class="block2">
			<image class="picture" src="../../static/icon-gl@3x.png"></image>
			<view class="font1">提现账户管理</view>
			<image src="../../static/icon-right@3x.png" class="picture2" @click="touch3()"></image>
			</view>
			<view class="block"></view>
		</view>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			touch1(){
				
			},
			touch2(){
				
			},
			touch3(){
				
			}
		}
	}
</script>

<style>
	.block{
		width: 100%;
		height: 2px;
		background-color: #e6e5ea;
	}
	.block1{
		
	}
	.block2{
		display: flex;
	}
.picture{
	margin: 10px;
	width: 20px;
	height: 20px;
	display: flex;
}
.picture1{
	margin-top: 15px;
	margin-left: 55%;
	width: 10px;
	height: 15px;
	
}
.picture2{
	margin-top: 15px;
	margin-left: 46%;
	width: 10px;
	height: 15px;
	
}
.font1{
	font-size: small;
	color: #666666;
	margin: 10px;
}
</style>

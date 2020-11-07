<template>
	<view>
		<view class="block1">
		<view class="add">+</view>
		<view class="font1">添加提现账户</view>
		</view>
		<view class="block2">
		</view>
		<view class="block3">
			<view class="font2">提现金额</view>
			<view class="block31">
				<view class="font5">¥</view>
				<input class="font3" placeholder="可提现金额" />
				<view class="font4">全部提现</view>
			</view>
		</view>
		<button class="block4">提现</button>
	</view>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
			
		}
	}
</script>

<style>
	.add{
		color: #8F8F94;
		margin-left: 15px;
		margin-right: 15px;
		margin-top: 15px;
	}
	.font1{
		color: #8F8F94;
		font-size: smaller;
		margin-top: 15px;
	}
	.font2{
		font-size: smaller;
		color: #8F8F94;
		margin-left: 15px;
	}
	.font3{
		width: 200px;
		font-size: larger;
		color: #8F8F94;
		margin:15px;
	}
	.font4{
		color:#df9543;
		font-size: smaller;
		margin-top: 20px;
		}
		.font5{
			color: #000000;
			font-size: larger;
			margin:10px;
		}
	.block1{
		
		display: flex;
		height: 50px;
		width: 100%;
	}
	.block2{
		background-color: #e1e1e7;
		height: 10px;
	}
	.block3{
		height: 100px;
	}
	.block31{
		display: flex;
	}
	.block4{
		width: 702rpx;
		height: 88rpx;
		background-color: #eb9229;
		box-shadow: 4rpx -2rpx 24rpx 0rpx 
		rgba(4, 0, 0, 0.16);
		border-radius: 44rpx;
		font-family: PingFang-SC-Medium;
		font-size: 36rpx;
		font-weight: normal;
		font-stretch: normal;
		color: #F1F1F1;
	}
</style>

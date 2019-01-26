<template>
	<view class="content">
		<!-- #ifdef APP-PLUS -->
		<image src="../../static/img1.png" mode="widthFix"></image>
		<!-- #endif -->
		<!-- #ifdef MP-WEIXIN -->
		<image src="../../static/img2.png" mode="widthFix"></image>
		<!-- #endif -->
		<!-- #ifdef H5 -->
		<image src="../../static/img1.png" mode="widthFix"></image>
		<!-- #endif -->
	</view>
</template>

<script>
export default {
	data() {
		return {
			title: 'Hello'
		};
	},
	onLoad() {},
	methods: {}
};
</script>

<style>
.content {
	text-align: center;
	height: 400upx;
}
.logo {
	height: 200upx;
	width: 200upx;
	margin-top: 200upx;
}
.title {
	font-size: 36upx;
	color: #8f8f94;
}
</style>

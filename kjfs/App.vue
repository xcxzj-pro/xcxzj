<script>
export default {
	onLaunch: function() {
		console.log('App Launch');

		setTimeout(() => {
// 			uni.setTabBarBadge({
// 				index: 1,
// 				text: '0'
// 			});
// 			uni.showTabBarRedDot({
// 				index: 3
// 			});
		}, 1000);
	},
	onShow: function() {
		console.log('App Show');
	},
	onHide: function() {
		console.log('App Hide');
	}
};
</script>

<style>
	@import './common/uni.css';
	/*每个页面公共css */
	page,view{
		display: flex;
	}
</style>

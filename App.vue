<script>
	export default {
		onLaunch: function() {
			console.log('App Launch1')
		},
		onShow: function() {
			console.log('App Show')
		},
		onHide: function() {
			console.log('App Hide')
		}
	}
</script>

<style>
	/*每个页面公共css */
	/* #ifndef APP-PLUS-NVUE */
	/* 官方ui库 */
	@import "/common/uni.css";
	/* 第三方动画库 */
	@import "/common/animate.css";
	/* 自定义图标库 */
	@import "/common/icon.css";
	/* UI基础库 */
	@import "/common/zcm-main.css";
	/* #endif */
	/* #ifdef APP-NVUE */
	@import "/common/zcm-main-nvue.css";
	/* #endif */
	/* 公共样式 */
	@import "/common/common.css";
</style>

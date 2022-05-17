<template>
	<div class="footer">
		<div class="top">
			<div class="shoppingGuide">
				<div class="title">
					购物指南
				</div>
				<div class="text">
					购物流程
				</div>
				<div class="text">会员介绍</div>
				<div class="text">生活旅行</div>
				<div class="text">常见问题</div>
				<div class="text">大家电</div>
				<div class="text">联系客服</div>
			</div>
			<div class="distribution">
				<div class="title">配送方式</div>
				<div class="text">上门自提</div>
				<div class="text">211极限送达</div>
				<div class="text">配送服务查询</div>
				<div class="text">配送费收取标准</div>
				<div class="text">海外配送</div>
			</div>
			<div class="pay">
				<div class="title">支付方式</div>
				<div class="text">货到付款</div>
				<div class="text">在线支付</div>
				<div class="text">分期付款</div>
				<div class="text">公司转账</div>
			</div>
			<div class="afterSale">
				<div class="title">售后服务</div>
				<div class="text">售后政策</div>
				<div class="text">价格保护</div>
				<div class="text">退款说明</div>
				<div class="text">返修/退换货</div>
				<div class="text">取消订单</div>
			</div>
			<div class="special">
				<div class="title">特色服务</div>
				<div class="text">夺宝岛</div>
				<div class="text">DIY装机</div>
				<div class="text">延保服务</div>
				<div class="text">尚品汇E卡</div>
				<div class="text">尚品汇通信</div>
			</div>
			<div class="area">
				<div class="title">尚品汇覆盖区县</div>
				<div class="text">尚品汇已向全国2661个区县提供自营配送服务，支持货到付款，pos机刷卡和售后上门服务</div>
			</div>
		</div>
		<div class="bottom">
			<div class="bottom-main">
				<div class="main-text">关于我们</div>
				<div class="main-text">联系我们</div>
				<div class="main-text">联系客服</div>
				<div class="main-text">合作招商</div>
				<div class="main-text">商家帮助</div>
				<div class="main-text">营销中心</div>
				<div class="main-text">手机尚品汇</div>
				<div class="main-text">友情链接</div>
				<div class="main-text">销售联盟</div>
				<div class="main-text">尚品汇社区</div>
				<div class="main-text">风险监测</div>
				<div class="main-text">隐私政策</div>
				<div class="main-text">尚品汇公益</div>
				<div class="main-text">English Site</div>
				<div class="main-text">Media & IR</div>
			</div>
			<div class="licence">
				<div class="licence-block">
					<div class="licence-text">出版物经营许可证</div>
					<div class="licence-text">地址：北京市昌平区宏福科技园综合楼6层</div>
				</div>
				<div class="licence-block">
					<div class="licence-text">京ICP备19006430号</div>
				</div>
			</div>
		</div>
	</div>
</template>

<script>
</script>

<style scoped="scoped">
	*{
		margin: 0px; padding: 0px;
		background-color: #F4F4F4;
	}
	.top{
		height: 200px; background-color: #f4f4f4; display: flex; justify-content: space-around; border-top: 1px solid #dedede; border-bottom: 1px solid #dedede;
	}
	.title{
		font-size: 14px; color: #666666; font-weight: 700; margin-top: 24px; margin-bottom: 11px;
	}
	.text{
		font-size: 12px; color: #666666; line-height: 22px;
	}
	.top .area {
		width: 184px;
	}
	.bottom{
		margin-top: 16px;
	}
	.bottom .bottom-main{
		display: flex;
		justify-content: center;
	}
	.bottom-main .main-text{
		height: 12px; border-right: 1px solid #e1e1e1; padding: 0 10px;
		font-size: 12px; font-weight: 400; line-height: 12px; color: #666666;
	}
	.bottom-main .main-text:last-child{
		border: none;
	}
	.bottom .licence{
		margin-top: 16px;
	}
	.licence .licence-block{
		margin-top: 8px;
		display: flex;
		justify-content: center;
	}
	.licence-block .licence-text{
		height: 14px; font-size: 14px; line-height: 14px; border-right: 1px solid #e1e1e1; padding: 0 10px;
		color: #999999;
	}
	.licence-block .licence-text:last-child{
		border: none;
	}
</style>

<template>
	<div>
		<!-- 头部第一行 -->
		<div class="top">
			<div class="container">
				<div class="loginList">
					<p>尚品汇欢迎您</p>
					<p>
						<span>请</span>
						<a href="###">登录&nbsp;&nbsp;&nbsp;&nbsp;</a>
						<a href="###" class="register" style="color: #f10215;">免费注册</a>
					</p>
				</div>
				<div class="typeList">
					<a href="###">我的订单</a>
					<a href="###">我的购物车</a>
					<a href="###" style="color: #f10215;">我的尚品汇</a>
					<a href="###">尚品汇会员</a>
					<a href="###">企业采购</a>
					<a href="###">关注尚品汇</a>
					<a href="###">合作招商</a>
					<a href="###">商家后台</a>
				</div>
			</div>
		</div>
		<!-- 头部第二行  搜索区域 -->
		<div class="bottom">
			<h1 class="logoArea">
				<a href="###" class="logo" title="尚品汇" target="_blank">
					<img src="../../assets/logo.png" alt="" >
				</a>
			</h1>
			<div class="searchArea">
				<form action="###" class="searchForm">
					<input type="text" id="autocomplete" class="input-error input-xxlarge" value="" />
					<button class="sui-btn btn-xlarge btn-danger" type="button">搜索</button>
					<div class="searchForm-link">
						<a href="###">满199减100</a>
						<a href="###">奶酪棒</a>
						<a href="###">超薄冰箱</a>
						<a href="###">1+会员日</a>
						<a href="###">服饰满减</a>
						<a href="###">iPhone13</a>
						<a href="###">健康年礼</a>
						<a href="###">京东京造</a>
						<a href="###">小米手机</a>
					</div>
					<div class="shoppingCart">
						我的购物车
					</div>
				</form>
				<div class="searchArea-link">
					<a href="###">秒杀</a>
					<a href="###">优惠券</a>
					<a href="###">PLUS会员</a>
					<a href="###">品牌闪购</a>
					<a href="###">拍卖</a>
					<a href="###">京东家电</a>
					<a href="###">京东超市</a>
					<a href="###">京东生鲜</a>
					<a href="###">京东国际</a>
					<a href="###">京东云</a>
				</div>
			</div>
			<div class="recommendImg">
				<a href="###" class="recommendImg-logo" title="推荐" target="_blank">
					<img src="../../assets/logo.png" alt="" >
				</a>
			</div>
		</div>
	</div>
	
</template>

<script>
</script>

<style scoped="scoped">
	*{
		margin: 0px;
		padding: 0px;
	}
	a{
		text-decoration: none;
		color: #999999;
	}
	.top{
		width: 100%; height: 32px;
		background-color: #e3e4e5;
		font-size: 14px;
		line-height: 32px;
		color: #999999;
	}
	.container{
		display: flex;
		/* width: 434px; */
	}
	.loginList{
		display: flex;
		width: 400px;
		justify-content: space-around;
	}
	.top .typeList{
		
	}
	.typeList a{
		padding-left: 10px;
		padding-right: 10px;
		border-right: #999999 1px solid;
	}
	.typeList a:last-child {
		border: none;
	}
	
	.bottom{
		height: 140px; width: 100%; display: flex;
	}
	.bottom .logoArea{
		width: 300px;
	}
</style>

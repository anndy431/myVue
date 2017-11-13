<template>
    <ul class="footer-nav">
    	<li>
    		<a href="">
    			<i class="icon index-icon"></i>
    			<p>首页</p>
    		</a>
    	</li>
    	<li>
    		<a href="">
    			<i class="icon index-icon"></i>
    			<p>附近门店</p>
    		</a>
    	</li>
    	<li>
    		<a href="">
    			<i class="icon index-icon"></i>
    			<p>个人中心</p>
    		</a>
    	</li>
    	<div class="clear"></div>
    </ul>
</template>

<style lang="scss" scoped>
    .footer-nav li{
        width:33%;
        float:left;
    }
    .footer-nav{
    	width:100%;
    	border-top:1px solid #ccc;
    	background:#fff;
    	position:fixed;
    	left:0;
    	bottom:0;
    }
    .footer-nav li:nth-child(2){
        width:34%;
    }
    .footer-nav li a{
    	display:block;
    	text-align:center;
    	font-size:.6rem;
    	color:#333;
    	height:2.45rem;
    }
</style>
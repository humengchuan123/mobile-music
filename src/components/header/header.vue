<template>
	<div class="header">
		  <div class="icon"></div>
		  <h1 class="text">移动音乐</h1>
		  <div class="dowload">下载</div>
	</div>

		
</template>

<script>
export default{
	data() {
		return {}
	}
}	
</script>

<style lang="scss" scoped>
	.header{
	position: relative;
    height: 60px;
    text-align: left;
    color:#fff;
    background: #31c27c;
    font-size: 22px;
	}
	.header .icon{
	display: inline-block;
    vertical-align: top;
    margin-top: 12px;
    width: 30px;
    height: 32px;
    margin-left: 10px;
    background: url(logo@2x.png) no-repeat;
    background-size: 30px 32px;
        }
    .header .text{
      display: inline-block;
      vertical-align: top;
      line-height: 60px;
      color: rgba(255, 255, 255, 0.72);
    }
    .header .dowload{
        display: inline-block;
        vertical-align: top;
    	position: absolute;
    	width: 50px;
    	height: 30px;
    	line-height: 30px;
    	right: 0;
    	margin-top:12px;
    	margin-right: 8px;
    	border: 2px solid rgba(255, 255, 255, 0.72);
    	border-radius: 99px;
    	font-size: 18px;
    	text-align: center;
    }
</style>
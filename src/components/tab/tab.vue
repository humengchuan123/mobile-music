<template>
	<div class="tab">
  <keep-alive>
	<router-link tag="div" class="tab-item" to="/recommend">
      <span class="tab-link">推荐</span>
    </router-link>
  </keep-alive>
    <router-link tag="div" class="tab-item" to="/singer">
      <span class="tab-link">歌手</span>
    </router-link>
    <router-link tag="div" class="tab-item" to="/rank">
      <span class="tab-link">排行</span>
    </router-link>
    <router-link tag="div" class="tab-item" to="/search">
      <span class="tab-link">搜索</span>
    </router-link>

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
	.tab{
	display: flex;
    height: 44px;
    line-height: 44px;
    font-size: 20px;
     }

    .tab-item{
    flex: 1;
    text-align: center;
    }
    .tab-link{
    	padding-bottom: 5px;
      color: #333;
    }
     .router-link-active{
          border-bottom: 2px solid #31c27c;
        }     
     
      	
         
      
      
        
   

</style>
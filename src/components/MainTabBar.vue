<template>
  <tab-bar>
 
      <tab-bar-item link='/home'>
        <template v-slot:item-icon>
          <img  src="~assets/logo.png" alt="">
        </template>
        <template v-slot:item-icon-active>
          <img src="~assets/img/heima.png" alt="">
        </template>
        <template v-slot:item-text>
          <div>首页</div>
        </template>
      </tab-bar-item>

      <tab-bar-item link='/catagory'>
        <template v-slot:item-icon>
          <img  src="~assets/logo.png" alt="">
        </template>
        <template v-slot:item-icon-active>
          <img src="~assets/img/heima.png" alt="">
        </template>
        <template v-slot:item-text>
          <div>分类</div>
        </template>
      </tab-bar-item>

      <tab-bar-item link='/cart'>
        <template v-slot:item-icon>
          <img  src="~assets/logo.png" alt="">
        </template>
        <template v-slot:item-icon-active>
          <img src="~assets/img/heima.png" alt="">
        </template>
        <template v-slot:item-text>
          <div>购物车</div>
        </template>
      </tab-bar-item>

      <tab-bar-item link='/profile'> 
        <template v-slot:item-icon>
          <img  src="~assets/logo.png" alt="">
        </template>
        <template v-slot:item-icon-active>
          <img src="~assets/img/heima.png" alt="">
        </template>
        <template v-slot:item-text>
          <div>我的</div>
        </template>
      </tab-bar-item>

    </tab-bar>
</template>

<script>

import TabBar from "components/tabbar/TabBar";
import TabBarItem from "components/tabbar/TabBarItem.vue";

export default {
    name: 'MainTabBar',
    components: {
        TabBar,
        TabBarItem
    }
}
</script>

<style>

</style>
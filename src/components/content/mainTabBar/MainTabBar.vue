<template>
  <tab-bar>
      <tab-bar-item path="/home">
        <img slot="item-icon" src="~assets/img/tabbar/item-home.png" alt=""/>
        <img slot="item-icon-active" src="~assets/img/tabbar/item-home-active.png" alt=""/>
        <div slot="item-text">首页</div>
      </tab-bar-item>
      <tab-bar-item path="/category">
        <img slot="item-icon" src="~assets/img/tabbar/item-category.png" alt=""/>
        <img slot="item-icon-active" src="~/assets/img/tabbar/item-category-active.png" alt=""/>
        <div slot="item-text">分类</div>
      </tab-bar-item>
      <tab-bar-item path="/shopcart">
        <img slot="item-icon" src="~assets/img/tabbar/item-shopcart.png" alt=""/>
        <img slot="item-icon-active" src="~assets/img/tabbar/item-shopcart-active.png" alt=""/>
        <div slot="item-text">购物车</div>
      </tab-bar-item>
      <tab-bar-item path="/user">
        <img slot="item-icon" src="~assets/img/tabbar/item-user.png" alt=""/>
        <img slot="item-icon-active" src="~assets/img/tabbar/item-user-active.png" alt=""/>
        <div slot="item-text">我的</div>
      </tab-bar-item>
    </tab-bar>
</template>
<script>

import TabBar from "components/common/tabbar/TabBar"
import TabBarItem from "components/common/tabbar/TabBarItem"
export default {
  name:'MainTabBar',
  components: {
    TabBar,
    TabBarItem
  }
}
</script>

<style scoped>

</style>


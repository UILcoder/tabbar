<template>
  <div id='MainTabbar'>
      <tabbar>
       <tabbaritem path="/home" activeColor="#d4237a">
         <img slot="item-icon" src="~assets/img/tabbar/home .svg" />
         <img slot="item-icon-active" src="~assets/img/tabbar/home-1.svg" />
         <div slot="item-text"> 首页 </div>
       </tabbaritem>
       <tabbaritem path="/sort" activeColor="yellow">
         <img slot="item-icon" src="~assets/img/tabbar/sort.svg" />
         <img slot="item-icon-active" src="~assets/img/tabbar/sort-1.svg" />
         <div slot="item-text"> 分类 </div>
       </tabbaritem>
         <tabbaritem path="/cart" activeColor="green">
         <img slot="item-icon" src="~assets/img/tabbar/cart.svg" />
         <img slot="item-icon-active" src="~assets/img/tabbar/cart-1.svg" />
         <div slot="item-text"> 购物车 </div>
       </tabbaritem>
       <tabbaritem path="/user" activeColor="white">
         <img slot="item-icon" src="~assets/img/tabbar/user.svg" />
         <img slot="item-icon-active" src="~assets/img/tabbar/user-1.svg" />
         <div slot="item-text"> 我的 </div>
       </tabbaritem>
    </tabbar>
  </div>
</template>

<script>
import tabbar from 'components/tabbar/tabbar';
import tabbaritem from 'components/tabbar/tabbaritem';
//或者导入TabBar、TabBarItem相对应模板中的tab-bar、tab-bar-item 
export default {
    name:"MainTabbar",
    components: {
    tabbaritem,
    tabbar
  }

}
</script>

<style>

</style>
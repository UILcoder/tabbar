<template>
  <div id="tab-bar">
     <slot></slot>
  </div>
</template>

<script>
export default {
  name:'tabbar'
}
</script>

<style>
    #tab-bar{
    display: flex;
    background-color: rgb(226, 224, 224);
    position: fixed;
    bottom: 0;
    left: 0;
    right: 0;
    box-shadow: 0 -1px 1px rgba(145, 142, 142, 0.3);
  }

</style>
<template>
  <div class="border2">
    <h3 :style="{ color: theme1.color }">F 节点</h3>
  </div>
</template>
<script>
export default {
  components: {},
  inject: {
    theme1: {  //为了避免名字重复起的别名
      from: "theme",  //真名在这个from中
      default: () => ({})
    }
  }
};
</script>

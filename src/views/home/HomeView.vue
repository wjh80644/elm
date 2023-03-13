<template>
  <div>
    <HeadView />
    <div class="cityTip">
      <span>当前定位城市：</span>
      <span>定位不准时，请在城市列表中选择</span>
    </div>
  </div>
</template>

<script>
import HeadView from '@/views/home/components/HeadView.vue';

export default {
  name: 'HomeView',
  components: {
    HeadView,
  },
};
</script>

<style lang="less" scoped>
@import '../../style/mixin';
.cityTip {
  margin-top: 2rem;
  border: 1px solid @gray;

  span:nth-child(1) {
    .sizeColor(0.5rem,#333);
  }

  span:nth-child(2) {
    font-size: 0.2rem;
  }
}
</style>

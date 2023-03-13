<template>
  <div id="head">
    <span class="home">首页</span>
    <span class="login">登录|注册</span>
  </div>
</template>

<style lang="less" scoped>
@import '../../../style/mixin.less';
#head {
  background: @blue;
  position: fixed;
  display: flex;
  top: 0;
  left: 0;
  .wh(100%, 2rem);

  .home {
    flex: 1;
    line-height: 2rem;
    margin-left: 0.5rem;
    .sizeColor(0.65rem, @white);
  }

  .login {
    flex: 1;
    text-align: right;
    line-height: 2rem;
    margin-right: 0.5rem;
    .sizeColor(0.65rem, @white);
  }
}
</style>

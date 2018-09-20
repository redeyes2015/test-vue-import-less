<template>
  <div>
    Hello world.
  </div>
</template>

<script>
import './a.less';

export default {
};
</script>

<style lang="less" src="./b.less" scoped />
<style lang="less" src="./c.less" />

<style lang="less" scoped>
@import './d.less';
@import (reference) './e.less';
</style>

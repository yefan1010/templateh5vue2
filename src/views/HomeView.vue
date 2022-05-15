<template>
  <div class="home">
    <div>
<van-button type="primary">主要按钮</van-button>
<van-button type="info">信息按钮</van-button>
    </div>
  </div>
</template>

<script>
import { Button } from 'vant';
export default {
  name: 'HomeView',
  components: {
    [Button.name]: Button,
  }
}
</script>
<style scoped>
.home {
  height: 500px;
  width: 500px;
  background-color: pink;
}
</style>>
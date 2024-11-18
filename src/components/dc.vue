<!--
 * @Author: dc 1090504489@qq.com
 * @Date: 2024-11-18 15:02:18
 * @LastEditors: dc 1090504489@qq.com
 * @LastEditTime: 2024-11-18 15:02:33
 * @FilePath: \vue3-git-demo\src\components\dc.vue
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <div></div>
</template>

<script>
import { reactive, toRefs } from "vue";

export default {
  setup() {
    const state = reactive({
      count: 0,
    });

    return {
      ...toRefs(state),
    };
  },
};
</script>

<style lang="scss" scoped></style>

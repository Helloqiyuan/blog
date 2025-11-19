<template>
<div>
  <n-avatar
   style="width: 100%;height: 100%"
      src="https://qiyuan-cloud-data.oss-cn-guangzhou.aliyuncs.com/pinkavatar.jpg"
  />

</div>
</template>

<script setup lang="ts">
import {VaeStore} from "../../store";
import {storeToRefs} from "pinia";
const store = VaeStore();
let {clientWidth} = storeToRefs(store);

</script>

<style scoped>

</style>

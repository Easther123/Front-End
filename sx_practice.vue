<!--
 * @Author: weixin_51773378 weixin_51773378@noreply.gitcode.com
 * @Date: 2024-07-09 10:54:08
 * @LastEditors: weixin_51773378 weixin_51773378@noreply.gitcode.com
 * @LastEditTime: 2024-07-09 10:54:14
 * @FilePath: \前端练习\sx_practice.html
 * @Description: 这是默认设置,请设置`customMade`, 打开koroFileHeader查看配置 进行设置: https://github.com/OBKoro1/koro1FileHeader/wiki/%E9%85%8D%E7%BD%AE
-->
<template>
  <!--HTML-->
  <div>
    <h1>{{count}}</h>
    <button @click="foo()">Click Me</button>
  </div>
</template>

<script setup>
import {ref} from "vue";

const foo=()=>{
  count.value++;
}

const count=ref(0);
</script>
<style scoped>
  
</style>
<template>
    <!-- <html></html> -->
    <div class="app">
        <h1>你好啊</h1>
        <Person/>
    </div>
</template>
<script lang="ts">
// js/ts
import Person from "./components/Person.vue";
export default {
    name:'App',//组件名字
    components:{Person},//注册组件
    data(vm) {
        
    },
}
</script>

<style>
/* 样式 */
.app{
    background-color: #ddd;
    box-shadow: 0 0 10px;
    height: 120px;
}
</style>
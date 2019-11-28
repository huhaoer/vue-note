<!-- 组件模板   在template中写dom元素 -->
<template>
    <div>i am a div</div>
</template>

<!-- 将模板以外的东西都写在script里面 -->
<script>
export default {
    data() {
        return {
            msg : 'hello world'
        }
    }
}
</script>

<!-- style写css样式的 -->
<style>
    div {
        width: 100px;
        height: 100px;
        color: #fff;
        background-color: red;
    }
</style>

<!-- 使用vue serve app.vue(组件名)可以运行
     如果组件名就是App.vue的话,就可以直接用vue serve运行
 -->


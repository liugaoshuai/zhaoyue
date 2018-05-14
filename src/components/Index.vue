<template>
  <div class="hello">
    <h1 v-if="ok">{{ msg }}</h1>
    <h2>hello zhaoyue</h2>
    <p>1.根据官网提示安装vue <a href="https://cn.vuejs.org/v2/guide/installation.html" target="_blank">点击链接</a></p>
    <p>2.根据vue文档实现v-bind v-model v-show v-if v-else 也就是vue教程里的基础 例子全部自己实现一遍</p>
    <p>3.根据element-ui官网安装element-ui 以及配置 <a href="http://element.eleme.io/#/zh-CN" target="_blank">点击链接</a></p>
    <p>4.实现ui框架按钮表单表格各种展现形式 一直配置对组件的影响</p>
    <!-- <p>4.了解vue-router组件<a href="https://router.vuejs.org/zh-cn/" target="_blank">点击链接</a></p><p>2.根据element-ui官网安装element-ui 以及配置 <a href="http://element.eleme.io/#/zh-CN" target="_blank">点击链接</a></p> -->
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
      msg: 'Welcome to Your Vue.js Appasdas',
      ok: true,
    }
  },
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h1, h2 {
  font-weight: normal;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>

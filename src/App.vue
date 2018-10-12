<template>
  <div id="app">
    <app-header></app-header>
    <users></users>
    <app-footer></app-footer>
  </div>
</template>
<script>
//局部注册组件
import Users from "./components/users";
import Header from "./components/Header";
import Footer from "./components/Footer";
export default {
  name: 'App',
  components: {
    // Users
    "users": Users,
    "app-header": Header,
    "app-footer": Footer
  },
  data(){
    return {
      title: "这是我的第一个vue cli程序"
    }
  }
}
</script>
<style scoped>
h1{color:purple}
</style>

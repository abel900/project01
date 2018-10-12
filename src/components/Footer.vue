<template>
  <footer>
      <p>{{copyright}}</p>
  </footer>
</template>
<script>
export default {
  name: 'app-footer',
  data () {
    return {
      copyright: "copyright 2017 vue demo"
    }
  }
}
</script>
<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
footer{
  background:rgb(238, 155, 96);
  padding: 10px;
}
p{color: #222;text-align: center;}
</style>
<template>
    <div id="app">
      <img alt="Vue logo" src="./assets/ying.jpg">
    </div>
    <div class="style1">基本信息</div>
    <div :style="{fontSize:'20px'}">姓名:{{myname}}</div>
    <div :style="{fontSize:'20px'}">学号:{{number}}</div>
    <div class="style1">兴趣爱好</div>
     <div :style="{fontSize:'20px'}">羽毛球</div>
</template>

<script>


export default {
  name: 'App',
    data(){
        return{
            myname:"温嘉伟",
            number: 2310273028
        }
    }
}
</script>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
  .style1{
    font-size:40px;
    font-weight:bold;

  }
}
</style>

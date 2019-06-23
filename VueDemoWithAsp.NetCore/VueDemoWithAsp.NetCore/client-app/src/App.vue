<template>
  <div id="app" class="newapp">
    <img alt="Vue logo" id="newlogo" src="./assets/dotnetcore-vue.jpg">
      <input type="hidden" id="hintidentifier" value="dotnetcore"/>
    <HelloWorld msg="This is my first vue application"/>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'

export default {
  name: 'app',
  components: {
    HelloWorld
  }
}
</script>

<style>
    .newapp{
        text-align:center;
        margin-top:50px;    
    }
</style>

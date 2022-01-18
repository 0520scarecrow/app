<template>
  <div id="app">
    <!-- <img alt="Vue logo" src="./assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/> -->
	<Header></Header>
  </div>
</template>

<script>
import HelloWorld from './components/HelloWorld.vue'
import Header from './components/Header/index.vue'

export default {
  name: 'App',
  components: {
    Header
  }
}
</script>

<style>
	*{
		margin: 0px;
		padding: 0px;
	}
</style>

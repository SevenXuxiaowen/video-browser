<template>
  <div>
    <SearchBar @onTermChange="onTermChange"></SearchBar>
  </div>
</template>

<script>
import SearchBar from './components/SearchBar';
const API_KEY = 'AIzaSyBydOE29bGLTSYZtjxVcgFnuUWcdwu-6M8';

export default {
  name: 'App',
  components:{
    SearchBar
  },
  methods:{
    onTermChange(term){
      console.log(term)
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
}
</style>

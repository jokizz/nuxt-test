<template>
  <div id="app">
    <tinymce id="d1" v-model="data"></tinymce>
  </div>
</template>

<script>

export default{
    data(){
        return {
            data : ''
        };
    }
}
</script>

<style>
#app {
  font-family: 'Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>

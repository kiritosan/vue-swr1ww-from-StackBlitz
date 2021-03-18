<template>
  <div v-if="true">{{text}}</div>
  <div v-else></div>
</template>

<script>
  export default {
    data: function () {
      return {text:'X'}
    }
}
</script>

<style>
  #app {
    
    text-align: center;
    border:1px;

  }
</style>
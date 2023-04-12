<template>
  <header> 
    <h1>{{ title }}</h1>
    <defaultButton text="Add Task" color="green"/>
  </header>
</template>

<script>
import defaultButton from './defaultButton.vue'

export default {
    name: 'page-header',
    props: {
      title: String,
    },
    components: {
      defaultButton
    }
  }
</script>

<style scoped>
  header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 20px;
  }
</style>
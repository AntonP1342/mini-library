<template>
  <div id="app">
    <div id="nav">
      <!-- <router-link to="/">Home</router-link> |
      <router-link to="/about">About</router-link> -->
    </div>
    <router-view/>

    <BooksArray/>
  </div>
</template>
<script>
export default {
  import BooksArray from '../components/BooksArray.vue'
  components:{BooksArray}
}
</script>

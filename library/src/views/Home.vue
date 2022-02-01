<template>
  <div class="home">
    <h1>Books Library</h1>
    <router-link to="/readinglist"><button>Reading List</button></router-link>
    <router-link to="/book"><img src="../assets/Library.png" alt=""></router-link>

  </div>
</template>

<script>
export default {
    
}
</script>

<style lang=sass>
.home a button
  padding: 6px 30px
  background-color: #252525
  color: lightgrey
  border: none
  border-radius: 4px
  transition: background-color 0.5s ease, color 0.5s ease
.home a button:hover
  color: #252525
  background-color: lightgrey
</style>
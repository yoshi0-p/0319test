<template>
  <div class="about">
    <router-link to="/">Home</router-link>|
    <router-link to="/member">About</router-link>
    <p>{{id}}</p>
  </div>
</template>
<script>
export default {
  props: ["id"],
}
</script>


<style scoped>
p{
  text-align:center;
}
</style>

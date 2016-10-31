<template>
  <div>
    <h1 class="page-title">About</h1>
  </div>
</template>

<script>
  export default {
    name: 'about',
    path: '/about',

    data () {
      this.$http.get('/api/v1/post')
        .then(res => console.log(res.data))
      return {}
    }
  }
</script>

<style>

</style>

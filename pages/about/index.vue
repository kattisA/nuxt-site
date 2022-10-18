<template>
  <div>
    <Title :title="title"/>

  </div>

</template>

<script>
export default {
  name: 'About',
  layout: 'auth',
  data () {
    return {
      title: "About page"
    }
  }
}
</script>

<style>

</style>

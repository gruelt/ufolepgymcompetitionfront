<template>
  <div>
    <UINavBar :user="this.$store.state.auth.user.email"></UINavBar>



  </div>
</template>

<script>
export default {
  name: "about.vue",
  layout: "public"
}
</script>

<style scoped>

</style>

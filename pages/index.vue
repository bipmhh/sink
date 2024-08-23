<template>
  <main class="flex flex-col justify-center">

  </main>
</template>
<script>
export default {
  mounted () {
    const user = this.$store.state.auth.user
    if (user !== null) {
      if (this.$route.query.link) {
        window.location.href = this.$route.query.link
      } else {
        window.location.href = '/dashboard' // Some default link
      }
    } else {
      window.location.href = '/dashboard' // login page
    }
  }
}
</script>

<script setup>
import { BloggerIcon, GitHubIcon, GmailIcon, MastodonIcon, TelegramIcon, XIcon } from 'vue3-simple-icons'

const email = ref(null)
onMounted(() => {
  email.value.href = email.value.href.replace('$', '@')
})
</script>

<template>
  <section class="md:pt-6">
    .
  </section>
</template>

<script setup>
import { Ellipsis, X } from 'lucide-vue-next'
import { GitHubIcon } from 'vue3-simple-icons'
import SwitchTheme from '../SwitchTheme.vue'

const showMenu = ref(false)
</script>

<template>
  <section class="pb-6">
    <a
                class="w-full px-6 py-2 mr-0 text-gray-700 cursor-pointer dark:text-gray-300 md:px-3 md:mr-2 lg:mr-3 md:w-auto"
                href="/dashboard"
                title="Sink Dashboard"
              >Dashboard</a>
  </section>
</template>

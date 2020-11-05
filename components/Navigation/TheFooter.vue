<template>
  <footer v-if="isLoggedIn" class="bg-white">
    <div class="max-w-screen-xl mx-auto py-12 px-4 overflow-hidden space-y-8 sm:px-6 lg:px-8">
      <p class="mt-8 text-center text-base leading-6 text-gray-400">
        &copy; {{ new Date().getFullYear() }} Labandera, Inc. All rights reserved.
      </p>
    </div>
  </footer>
</template>

<script>
import Logo from '@/components/Logo'

export default {
  components: {
    Logo
  },
  data() {
    return {
      isLoggedIn: false
    }
  }
}
</script>

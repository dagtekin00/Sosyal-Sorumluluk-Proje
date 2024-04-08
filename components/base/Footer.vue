<template>
  <footer class="max-w-screen-xl px-8 mx-auto">
    <div class="w-full border-y border-[#DDDDDD]"></div>
    <div class="py-8 sm:py-4 text-center text-sm text-[#666666] hover:text-gray-900">
      <p>Tacettin Dağtekin - Oğuz Tümay - Ali Sağlamel</p>
      <img :src="require('~/assets/img/logo/logo.webp')" class="w-24 mt-5 mx-auto" alt="TTMTAL Logo" /><br />
      &copy; Copyright 2024 OTA LLC. All rights reserved
    </div>
  </footer>
</template>
<script>
export default {
  name: 'BaseFooter',
}
</script>

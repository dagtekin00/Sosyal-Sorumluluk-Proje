<template>
  <nav id="navbar" class="relative z-10 w-full text-neutral-800">
    <div class="flex flex-col max-w-screen-xl px-8 mx-auto lg:items-center lg:justify-between lg:flex-row py-4">
      <div class="flex flex-col lg:flex-row items-center space-x-4 xl:space-x-8">
        <div class="w-full flex flex-row items-center justify-between py-6">
          <div><img :src="require('~/assets/img/logo/logo.webp')" class="w-24 xl:w-28" alt="TTMTAL Logo" /></div>
          <button class="rounded-lg lg:hidden focus:outline-none focus:shadow-outline" @click="open = !open">
            <SegmentIcon v-if="!open" :size="24" />
            <CloseIcon v-else :size="24" />
          </button>
        </div>
        <ul
          :class="[open ? 'flex' : 'hidden lg:flex']"
          class="w-full gap-8 h-auto flex flex-col flex-grow lg:items-center pb-4 lg:pb-0 lg:justify-end lg:flex-row origin-top duration-300 xl:space-x-2 space-y-3 lg:space-y-0"
        >
          <nuxt-link to="/">AnaSayfa</nuxt-link>
          <nuxt-link to="/SigaraBagimlilik">Sigara</nuxt-link>
          <nuxt-link to="/MaddeBagimlilik">Madde </nuxt-link>
          <nuxt-link to="/TeknolojiBagimlilik">Teknoloji</nuxt-link>
          <nuxt-link to="/SiberZorbalik" class="w-max">Siber Zorbalık</nuxt-link>
          <nuxt-link to="/AlkolBagimlilik">Alkol</nuxt-link>
          <nuxt-link to="/SiddetBagimlilik">Şiddet</nuxt-link>
        </ul>
      </div>
    </div>
  </nav>
</template>
<script>
export default {
  name: 'BaseNavbar',
  data() {
    return {
      open: false,
      dropdownNavbar: false,
    }
  },
  methods: {
    dropdownToggler() {
      this.dropdownNavbar = !this.dropdownNavbar
    },
  },
}
</script>

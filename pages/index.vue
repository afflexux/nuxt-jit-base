<template>
  <div class="container flex flex-col">
    <h1
      class="py-8 text-transparent font-mono text-5xl font-black tracking-wide bg-gradient-to-r bg-clip-text from-blue-500 to-green-300 uppercase"
    >
      Gone Shopping
    </h1>
    <!-- <img src="~/assets/images/gleb-albovsky-a-0Qsar9rBg-unsplash.jpg" alt="" /> -->
    <nuxt-img
      provider="cloudinary"
      src="v1590172498/Unsplash/Medium/Blog/tzk--R_JYS4PbQM-unsplash.jpg"
      width="640"
      height="480"
      fit="coverLimit"
      :modifiers="{ rotate: 'ignore', effect: 'cartoonify:20:80' }"
    />
  </div>
</template>

<script>
export default {}
</script>

<style lang="postcss">
.container {
  @apply flex items-center justify-center mx-auto min-h-screen text-center;
}
</style>

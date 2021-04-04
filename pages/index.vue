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

<style>
/* Sample `apply` at-rules with Tailwind CSS
.container {
@apply min-h-screen flex justify-center items-center text-center mx-auto;
}
*/
.container {
  margin: 0 auto;
  min-height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  text-align: center;
}
</style>

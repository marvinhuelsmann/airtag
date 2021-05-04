<template>
  <div class="home">
    <div>
      <div class="mt-48 justify-center flex">
        <img class="animate-bounce content-center object-center lg:max-w-xl lg:max-h-xl ..." alt="AirTag" src="../assets/shopping.png">
      </div>
      <h1 class="xl:text-9xl text-7xl text-black antialiased font-bold 2xl:resize">
        AirTags
      </h1>
      <div class="mt-3.5 justify-center flex">
        <button formtarget="_blank"
            class="px-9 py-4 font-semibold rounded-md rounded-sm block sm:w-auto border-purple-300 bg-purple-200 hover:bg-purple-300 text-purple-700">
          <a href="https://www.apple.com/shop/buy-airtag/airtag">buy one at the Apple Website</a>
        </button>
      </div>
    </div>
    <Footer site-name="Home"/>
  </div>
</template>

<script>
// @ is an alias to /src
import Footer from '@/components/Footer.vue'

export default {
  name: 'Home',
  components: {
    Footer
  }
}
</script>

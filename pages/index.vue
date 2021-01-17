<template>
  <div class="font-sans bg-no-repeat bg-center bg-cover h-screen flex flex-col" :style="{'background-image': `url(${require('@/assets/header-bg.jpg')})`}" >
    <Nav />
    <div class="flex flex-col justify-center items-center h-full max-w-screen-sm m-auto text-center p-2">
      <h1 class="text-3xl md:text-4xl text-white font-bold tracking-wide leading-normal">
        CREATIVE DESIGN
      </h1>
      <p class="text-white">
        Enigma is a Creative Minimal Style Onepage. It is Fully Responsive and Retina Ready. Grab This Awesome Template Now.
      </p>
      <div class="flex justify-between mt-4">
        <button class="text-white py-2 px-4 rounded-none border border-white font-bold text-xs mr-2 hover:text-black hover:bg-white" >
          LEARN MORE
        </button>
        <button class="text-white py-2 px-4 rounded-none border border-white font-bold text-xs ml-2 hover:text-black hover:bg-white">
          PURCHASE IT
        </button>
      </div>
      
    </div>
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

</style>

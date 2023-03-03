
<template>
    <div class="py-3 px-4 md:px-36 shadow-md md:flex sticky justify-between md:items-center">
      <div class="flex items-center justify-between">
        <span>
          <img src="https://cdn.supervise.ly/img/logo.9fe28bd.png" class="md:h-10 md:w-40" alt="">
        </span>
        <button @click="showMenu = !showMenu" class="block md:hidden text-gray-500 hover:text-gray-300 focus:text-gray-400 focus:outline-none">
          <svg class="h-6 w-6 fill-current" viewBox="0 0 24 24">
            <path v-if="showMenu" fill-rule="evenodd" clip-rule="evenodd" d="M3 5h18a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2zm18 6H3a1 1 0 1 1 0-2h18a1 1 0 1 1 0 2zm0 6H3a1 1 0 1 1 0-2h18a1 1 0 1 1 0 2z"/>
            <path v-else fill-rule="evenodd" clip-rule="evenodd" d="M4 6h16v2H4V6zm0 6h16v2H4v-2zm0 6h16v2H4v-2z"/>
          </svg>
        </button>
      <div :class="{'block': showMenu, 'hidden': !showMenu}" class="md:flex md:items-center md:w-auto w-full">

        <ul class="md:flex justify-between md:px-0 md:pb-0 pb-10 md:static absolute md:space-x-5 font-semibold md:items-center cursor-pointer">
          <li class="hover:text-black md:mx-4"><a href="#">Platform</a></li>
          <li class="hover:text-black md:mx-4"><a href="#">Ecosystem</a></li>
          <li class="hover:text-black md:mx-4"><a href="#">Services</a></li>
          <li class="hover:text-black md:mx-4"><a href="#">Enterprise</a></li>
          <li class="hover:text-black md:mx-4"><a href="#">Pricing</a></li>
          <li class="hover:text-black md:mx-4"><a href="#">Blog</a></li>
          <li class="hover:text-black md:mx-4"><a href="#">Learn</a></li>
        </ul>
    </div>
      </div>
  
      <div :class="{'block': showMenu, 'hidden': !showMenu}" class="md:flex md:items-center md:w-auto w-full">
      
  
        <ul class="md:flex justify-between md:space-x-5 md:items-center cursor-pointer">
          <li class="md:my-0 my-6"><a href="#">Login</a></li>
          <li><a href="#">Get a demo</a></li>
          <li><button class="bg-pink-500 text-white py-2 px-4 rounded-full font-semibold hover:bg-pink-600">Try for free</button></li>
        </ul>
      </div>
    </div>
  </template>


<script>
export default {
  data() {
    return {
      showMenu: false
    };
  }
}
</script>

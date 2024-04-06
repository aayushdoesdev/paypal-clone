<script>
import "primeicons/primeicons.css";


export default{
  
}
</script>

<template>
  <div class=" h-20 flex items-center justify-between mx-8 lg:justify-center
  font-poppins space-x-24">
    <div class="flex items-center gap-6 cursor-pointer">
      <img
        src="https://www.paypalobjects.com/paypal-ui/logos/svg/paypal-mark-color.svg"
        alt="paypal"
        height="40"
        width="40"
      />
      <ul class="hidden lg:flex gap-2 list-none font-bold">
        <div
          class="flex items-center gap-2 cursor-pointer hover:bg-blue-200 px-4 py-2 rounded-full transition ease-out duration-300"
        >
          <li class="text-bold text-neutral-700">Personal</li>
          <i class="pi pi-angle-down" style></i>
        </div>
        <div
          class="flex items-center gap-2 cursor-pointer hover:bg-blue-200 px-4 py-3 rounded-full transition ease-out duration-300"
        >
          <li class="text-bold text-neutral-700">Small Business</li>
          <i class="pi pi-angle-down" style></i>
        </div>
        <div
          class="flex items-center gap-2 cursor-pointer hover:bg-blue-200 px-4 py-2 rounded-full transition ease-out duration-300"
        >
          <li class="text-bold text-neutral-700">Enterprise</li>
          <i class="pi pi-angle-down" style></i>
        </div>
        <div
          class="flex items-center cursor-pointer px-4 py-2"
        >
          <li class="text-extrabold hover:text-blue-900  text-blue-500 transition ease-out">Developer</li>
        </div>
      </ul>
    </div>



    <div class="flex items-center font-bold space-x-4">
      <ul class="hidden lg:flex items-center gap-2 list-none">
        <div class="flex items-center cursor-pointer px-4 py-2">
          <li
            class="text-bold text-neutral-700 hover:text-blue-500 transition ease-out"
          >
            What's new
          </li>
        </div>
        <div class="flex items-center cursor-pointer px-4 py-2">
          <li
            class="text-bold text-neutral-700 hover:text-blue-500 transition ease-out duration-300"
          >
            Help
          </li>
        </div>
      </ul>
      <div class="space-x-4 flex items-center">
        <button
          class="bg-transparent px-5 py-1 rounded-3xl border-2 border-blue-800 font-bold text-[16px] cursor-pointer"
        >
          Login
        </button>
        <button
          class=" px-5 py-2 rounded-3xl bg-blue-800 font-bold text-[15px] border-none cursor-pointer text-white"
        >
          Sign Up
        </button>
        <div class="lg:hidden">
        <i class="pi pi-bars text-2xl cursor-pointer"></i>
      </div>
      </div>
    </div>
  </div>
</template>

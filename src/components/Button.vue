<template>
      <button
          class=" px-6 py-2 rounded-3xl bg-blue-900 text-white font-bold text-[18px] cursor-pointer hover:bg-blue-700 transition ease-out"
        >
          {{ title }}
        </button>
</template>

<script>
    export default {
        name: "Button",
        props:{
          title: String
        }
    }
</script>


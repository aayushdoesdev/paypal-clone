<script>
import Button from "@/components/Button.vue"
export default {
    components:{
        Button
    }
};
</script>

<template>
  <div class="h-[105vh] lg:h-[85vh] bg-neutral-100 lg:flex items-center justify-center">
    <div class="lg:hidden">
      <img
        src="https://www.paypalobjects.com/marketing/web/US/en/rebrand/Home/Uncookied/mkt-US-page-Homepage-size-Table-up-Component-security.png?quality=75&width=800"
        alt=""
      />
    </div>
    <div class="px-10 space-y-3 lg:max-w-[80vh]">
        <h1 class="text-3xl font-bold text-blue-900">Pay it <span class="text-blue-500">safe</span></h1>
        <p class="font-medium">Your transactions are encrypted, helping to keep your identity and financial info safe.</p>
        <Button title="Shop Confidently with PayPal"/>
    </div>
    <div class="lg:flex hidden">
      <img
        src="https://www.paypalobjects.com/marketing/web/US/en/rebrand/Home/Uncookied/mkt-US-page-Homepage-size-Table-up-Component-security.png?quality=75&width=600"
        alt=""
      />
  </div>
  </div>
</template>

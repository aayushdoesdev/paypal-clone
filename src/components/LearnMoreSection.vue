<script>
import Button from "@/components/Button.vue"
export default {
    components:{
        Button
    }
};
</script>

<template>
  <div class="px-10 h-[120vh] lg:h-[50vh] lg:flex items-center justify-center lg:gap-24">
    <div class="lg:hidden">
      <img
        src="https://www.paypalobjects.com/marketing/web/US/en/rebrand/Home/Cookied/mkt-US-page-Homepage-size-Table-up-Component-creditcard.png?quality=75&width=600"
        alt="card"
      />
    </div>
    <div class=" hidden lg:flex">
      <img
        src="https://www.paypalobjects.com/marketing/web/US/en/rebrand/Home/Cookied/mkt-US-page-Homepage-size-Table-up-Component-creditcard.png?quality=75&width=500"
        alt="card"
      />
    </div>
    <div class="space-y-3 lg:max-w-[55vh]">
      <h1 class="text-blue-900 text-3xl font-bold">Add another <span class="text-blue-600"> <br> 3% on top</span></h1>
      <p class="">Put it on your PayPal Cashback Mastercard®. You'll earn unlimited 3% cash back on your PayPal purchases. And you'll earn unlimited 2% cash back on all of your other purchases. No rotating categories. No annual fee. Just unlimited cash back. Plus, no impact to your credit score if you're declined.</p>
    <Button title="Learn About the Card"/>
    <p class="font-medium">Subject to credit approval.</p>
    </div>
  </div>
</template>

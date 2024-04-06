<script>
import Button from "@/components/Button.vue";
export default {
  components: {
    Button,
  },
};
</script>

<template>
  <div class="h-[115vh] lg:flex items-center justify-center">
    <div class="px-5 lg:hidden">
      <img
        src="https://www.paypalobjects.com/marketing/web/US/en/rebrand/Home/Uncookied/mkt--US_page--Homepage_%20size--all_Component--Split-section-03.jpg?quality=75&width=800"
        alt=""
      />
    </div>
    <div class="px-8 space-y-4 lg:max-w-[70vh]">
      <h1 class="text-3xl font-bold text-blue-900">
        Watch it <span class="text-blue-500"> grow</span>
      </h1>
      <p>
        Roll all that cash back into a high-yield PayPal Savings account. You
        could earn 4.30% APY. That's earning cash on cash back.
      </p>
      <Button title="Sign Up for PayPal Savings" />
      <p class="font-medium">
        PayPal Balance account is required to use PayPal Savings. PayPal is a
        financial technology company, not a bank. Banking services provided by
        Synchrony Bank, Member FDIC.
      </p>
    </div>
    <div class="px-5 lg:flex hidden">
      <img
        src="https://www.paypalobjects.com/marketing/web/US/en/rebrand/Home/Uncookied/mkt--US_page--Homepage_%20size--all_Component--Split-section-03.jpg?quality=75&width=800"
        alt=""
        width="600"
        height="100"
      />
    </div>
  </div>
</template>

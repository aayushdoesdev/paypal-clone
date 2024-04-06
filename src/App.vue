<script setup>
import Navbar from "@/components/Navbar.vue";
import CashBackSection from "@/components/CashBackSection.vue"
import LearnMoreSection from "@/components/LearnMoreSection.vue"
import SavingsAccountSection from "@/components/SavingAccountSection.vue"
import SecuritySection from "@/components/SecuritySection.vue"
import FeaturesSection from "@/components/FeaturesSection.vue"
import Footer from "@/components/Footer.vue"
</script>

<template>
  <Navbar />

  <!-- Hero Section -->
  <div
    class="bg-blue-950 p-4 h-[120vh] lg:h-[87vh] font-poppins lg:flex  justify-between"
  >
    <div class=" space-y-4 lg:ml-28 lg:mt-14">
      <div
        class="flex gap-4 text-xl bg-white w-[280px] items-center justify-center px-8 h-[55px] rounded-[500px] cursor-pointer m-auto lg:m-0"
      >
        <h4 class="bg-neutral-300 px-5 py-2 rounded-3xl">Personal</h4>
        <h4>Business</h4>
      </div>
      <h1 class="text-white text-4xl text-center lg:text-5xl font-semibold lg:text-left">
        Join PayPal.<br />
        Earn a sweet <span class="text-blue-600">$20</span> <br />
        <span class="text-blue-600"> cash back.</span>
      </h1>
      <p class="text-white font-medium leading-6 text-center lg:text-left">
        Your first three purchases of $30 or more with PayPal, can earn <br />
        you $20 cash back (2,000 Rewards points). To claim this offer,<br />
        please hit the sign up button below.
      </p>
      <div class="flex items-center gap-5 cursor-pointer justify-center lg:justify-start">
        <p class="bg-white px-7 py-3 rounded-3xl font-semibold">Sign Up</p>
        <p  class=" border-2 border-white px-7 py-3 rounded-3xl font-semibold text-white">Learn More</p>
      </div>
      <p class="text-white font-extralight text-sm text-center lg:text-left">Max 160,000 rewards avail. Offer ends 30 days from sign up. Terms apply. Check offer for details. <span class="font-semibold underline cursor-pointer hover:text-blue-300"> Terms and exclusions apply.</span></p>
    </div>
    <div class="ml-20 mt-4 lg:mt-11">
      <img
        src="https://www.paypalobjects.com/marketing/web23/US/en/rebrand/Home/Redesigned-Home/Consumer/Hero/mkt--US_page--homepage_component--hero_size--tablet-up_T3.png?quality=100&width=800"
        alt="image"
      />
    </div>
  </div>
  <CashBackSection/>
  <LearnMoreSection/>
  <SavingsAccountSection/>
  <SecuritySection/>
  <FeaturesSection/>
  <Footer/>
</template>

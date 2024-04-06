<script>
    import Button from "@/components/Button.vue"
    export default {
        components:{
            Button
        }
    }
</script>


<template>
    <div class="flex flex-col lg:flex-row justify-center lg:items-center  h-[120vh] lg:h-[95vh]">
        <div class="lg:hidden">
            <img src="https://www.paypalobjects.com/marketing/web/US/en/rebrand/Home/Uncookied/mkt--US_page--Homepage_%20size--all_Component--Split-section-01.png?quality=75&width=600" alt="">
        </div>
       
        <div class="px-10 lg:px-18 space-y-6 lg:max-w-[80vh]">
            <h1 class="text-3xl lg:text-5xl font-bold text-blue-900">Get <span class="text-blue-500"> unlimited cash back</span> on your favorite brands</h1>
            <p class="lg:font-semibold">Save as many cash back1 offers as you want. Earn 2, 3, 4, 5% and more after you check out with PayPal. Check offers for details. <span class="font-bold underline text-blue-600 hover:text-blue-900 cursor-pointer">Terms and exclusions apply</span> </p>
            <Button title="Check Out The Offers"/>
        </div>
        <div class="hidden lg:flex">
            <img src="https://www.paypalobjects.com/marketing/web/US/en/rebrand/Home/Uncookied/mkt--US_page--Homepage_%20size--all_Component--Split-section-01.png?quality=75&width=500" alt="">
        </div>
        
    </div>
</template>




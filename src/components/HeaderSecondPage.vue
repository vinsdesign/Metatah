<script>
import FlowerIcon from '@/components/icons/FlowerIcon.vue'
import Buttons from '@/components/Buttons.vue'

export default {
  components: {
    FlowerIcon,
    Buttons
  }
}
</script>

<template>
  <header class="bg-hero w-full bg-cover h-[840px] flex justify-center flex-col">
    <section class="flex flex-col justify-center items-center">
      <h1
        class="font-ImperialScript text-8xl text-primary xxsm:text-[70px] xsm:text-[80px] sm:text-[90px] md:text-[100px] lg:text-[100px]"
      >
        Undangan
      </h1>
      <!-- image dec 1 -->
      <!-- <Decoration1 :style="{ width: 'w-[300px]', height: 'w-[500px]' }" /> -->
      <FlowerIcon
        class="xxsm:w-[230px] xxsm:h-[250px] xsm:w-[250px] xsm:h-[280px] sm:w-[280px] sm:h-[300px] md:w-[300px] md:h-[300px] lg:w-[390px] lg:h-[390px]"
      />
      <h1
        class="font-ImperialScript text-8xl text-primary xxsm:text-[70px] xsm:text-[80px] sm:text-[90px] md:text-[100px] lg:text-[100px]"
      >
        Metatah
      </h1>
    </section>
  </header>
</template>

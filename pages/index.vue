<template>
  <div class="container bleed">
    <div class="flex flex-col justify-between mb-10">
      <HeroSection />
      <SignUpForm />
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
import SignUpForm from '@/components/SignUpForm.vue'
import HeroSection from '@/components/HeroSection.vue'
export default Vue.extend({
  components: {
    HeroSection,
    SignUpForm,
  },
})
</script>

<style lang="postcss">
.bleed {
  @apply min-h-screen justify-center text-center mx-auto;
}

.subtitle {
  font-weight: 300;
  font-size: 42px;
  color: #526488;
  word-spacing: 5px;
  padding-bottom: 15px;
}

.links {
  padding-top: 15px;
}
</style>

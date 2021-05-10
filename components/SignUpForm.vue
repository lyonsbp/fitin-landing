<template>
  <div class="md:rounded-xl bg-brandGreen py-12 px-4 md:px-48 text-white">
    <h2 class="text-3xl font-semibold mb-2">
      Subscribe to our biweekly newsletter!
    </h2>
    <p>Get helpful tips to help you get in shape and stay in shape for life!</p>
    <form class="mt-4">
      <input
        v-model="firstName"
        class="rounded mr-2 pl-2 py-2 w-2/3 mb-2"
        placeholder="First Name"
      />
      <input
        v-model="lastName"
        class="rounded mr-2 pl-2 py-2 w-2/3 mb-2"
        placeholder="Last Name"
      />
      <input
        v-model="email"
        class="rounded mr-2 pl-2 py-2 w-2/3 mb-4"
        placeholder="Email"
      />

      <button class="block btn primary mx-auto">Sign Up</button>
    </form>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'
export default Vue.extend({
  data() {
    return {
      firstName: '',
      lastName: '',
      email: '',
    }
  },
})
</script>

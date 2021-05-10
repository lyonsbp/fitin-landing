<template>
  <section class="hero-section bg-center w-full flex items-center mb-12">
    <div class="text-left ml-10 lg:ml-20 text-white w-2/3 md:w-1/3">
      <h1 class="text-5xl font-semibold">
        Workout <span class="text-brandOrange">from anywhere!</span>
        Join the community for free!
      </h1>
      <p class="my-1">
        Unlimited access to the world’s best workouts from top trainers.
      </p>
      <button class="btn primary sign-up-btn capitalize font-semibold">
        SIGN UP FOR FREE
      </button>
    </div>
  </section>
</template>

<style lang="postcss" scoped>
.hero-section {
  min-height: 50vh;
  background: url('/hero-image.png');
  background-size: cover;
  background-repeat: no-repeat;
  background-position: center;
}
.sign-up-btn {
  background: linear-gradient(
    270.29deg,
    #f0420b 0.22%,
    #ff5722 49.46%,
    #fb6e42 99.74%
  );
}
</style>

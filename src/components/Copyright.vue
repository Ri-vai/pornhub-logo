<template>
  <div class="text-center mt-4">
    <h2 class="text-white">
      Explore our 
      <router-link to="/" @click.native="scrollToTop" class="text-2xl">Pornhub</router-link> and 
      <router-link to="/onlyfans" @click.native="scrollToTop" class="text-2xl">Onlyfans</router-link> logo styles.
    </h2>
    <h2 class="text-custom-primary font-bold mt-20 mb-20 text-3xl">Try it now!</h2>
  </div>
  <p class="text-center text-[#666]">
    Copyright © 2024 - 
    <a href="https://bitbear.net/?refcode=1ndyezv73" target="_blank">All rights reserved</a>
  </p>
</template>

<script>
export default {
  methods: {
    scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  }
}
</script>
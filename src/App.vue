<template>
  <div>
      <Navbar/>
      <Hero/>
      <div class="ig-feed p-8">
        <InstagramFeed v-for="item in 8" :key="item.id"></InstagramFeed>
      </div>
      <Contact/>
  </div>
</template>

<style>
.ig-feed {
    height: auto;
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(233px, 1fr));
    grid-gap: 13px;
}
</style>

<script>
import Hero from './components/Hero.vue';
import Navbar from './components/Navbar.vue';
import InstagramFeed from './components/InstagramFeed.vue';
import Contact from './components/Contact.vue';

export default {
  components: {
    Hero,
    Navbar,
    InstagramFeed,
    Contact
  }
}
</script>
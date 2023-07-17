<template>
  <div>
    <Hero />
    <Gallery />
    <LatestPost />
  </div>
</template>

<script>
import Hero from "../components/Hero.vue";
import Gallery from "../components/Gallery.vue";
import LatestPost from "../components/LatestPost.vue";
export default {
  name: "Home",

  components: { Gallery, LatestPost, Hero },
};
</script>

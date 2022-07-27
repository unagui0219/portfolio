<template>
  <div class="hero">
    <h1>Hayato Unagibuchi</h1>
  </div>
</template>
<script>
export default {
  data() {
    return {
      isFirstScene: false,
    };
  },
  mounted() {
    this.showFirstScene;
  },
  methods: {
    showFirstScene() {
      this.isFirstScene = true;
    },
  },
};
</script>
<style>
.hero {
  font-family: "Nanum Myeongjo", sans-serif;
  text-align: center;
}
.hero h1 {
  letter-spacing: 0.3rem;
  font-size: 4rem;
}
</style>

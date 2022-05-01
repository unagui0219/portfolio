<template>
  <div :class="classes">
    <div class="card-title">
      <h2>{{ title }}</h2>
    </div>
    <div class="card-body">
      {{ content }}
    </div>
  </div>
</template>
<script>
export default {
  name: "Card",
  props: {
    title: String,
    content: String,
    large: {
      type: Boolean,
      required: false,
      default: false,
    },
  },
  computed: {
    classes() {
      return {
        "card-default": true,
        "card-large": this.large,
      };
    },
  },
};
</script>
<style>
#nav {
  text-align: center;
}
.card-default {
  box-shadow: 0 0.5rem 1rem hsl(0 0% 0% / 20%);
  border-radius: 10px;
  width: 80%;
  padding: 0.5rem 1rem 1rem;
  background-color: #fff;
  margin: 0 auto 1rem;
}
.card-large {
  width: 80%;
}
.card-row {
  display: flex;
  flex-wrap: wrap;
  justify-content: center;
  margin: 2rem auto 0;
  width: 90%;
}
.card-body {
  margin: 0;
  padding: 0;
}
.card-cover {
  width: 25rem;
}
</style>

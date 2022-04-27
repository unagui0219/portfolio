<template>
  <div class="card">
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
  },
};
</script>
<style>
#nav {
  text-align: center;
}
.card {
  box-shadow: 0 0.5rem 1rem hsl(0 0% 0% / 20%);
  border-radius: 10px;
  width: 25%;
  padding: 0.5rem 1rem;
  background-color: #fff;
  margin-left: 1rem;
}
</style>

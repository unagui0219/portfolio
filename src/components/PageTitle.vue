<template>
  <div class="page-title">
    <div class="page-title_cover">
      <h1>{{ title }}</h1>
    </div>
  </div>
</template>
<script>
export default {
  name: "PageTitle",
  props: {
    title: String,
  },
};
</script>
<style>
.page-title {
  font-family: "Nanum Myeongjo", sans-serif;
  text-align: center;
  font-size: 2rem;
}
.page-title_cover {
  display: flex;
  align-items: center;
}
.page-title_cover:before,
.page-title_cover:after {
  content: "";
  flex-grow: 1;
  height: 1px;
  background: black;
  margin: 0 2em;
}
</style>

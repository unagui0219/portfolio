<template>
  <div class="interest">
    <PageTitle title="Interest" />
    <div class="interest-body">
      <div class="card-row" v-for="(item, index) in interestItems" :key="index">
        <Card :title="item.title" :content="item.content" large />
      </div>
    </div>
  </div>
</template>

<script>
import PageTitle from "@/components/PageTitle.vue";
import Card from "@/components/Card.vue";

export default {
  name: "Interest",
  components: {
    PageTitle,
    Card,
  },
  data() {
    return {
      interestItems: interestItems,
    };
  },
};

var interestItems = [
  {
    title: "興味のある事業",
    content: "タコスの実店舗販売、プラットフォーム事業、芸能関係",
  },
  {
    title: "興味のある技術",
    content: "機械学習、ブロックチェーン、IoT",
  },
  {
    title: "興味のある趣味",
    content: "キャンプ、釣り、バイク",
  },
];
</script>

<style></style>

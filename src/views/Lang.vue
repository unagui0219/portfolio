<template>
  <div class="lang">
    <PageTitle title="Lang" />
    <div class="card-row">
      <div class="card-cover" v-for="(item, index) in langItems" :key="index">
        <Card :title="item.title" :content="item.content" />
      </div>
    </div>
  </div>
</template>

<script>
import PageTitle from "@/components/PageTitle.vue";
import Card from "@/components/Card.vue";

export default {
  name: "Lang",
  data() {
    return {
      langItems: langItems,
    };
  },
  components: {
    PageTitle,
    Card,
  },
};
var langItems = [
  {
    title: "日本語",
    content:
      "22年使ってますが、この中で一番難しい言語だと思ってます。語彙力をもっと増やして、思考力のベースを固めていきたいです。",
  },
  {
    title: "HTML/CSS",
    content: "高校生の時から書いてます。CSS設計なども勉強しています。",
  },
  {
    title: "Ruby",
    content:
      "書き始めてから今年で4年目になります。プログラミング言語の中で一番書いてます。",
  },
  {
    title: "JavaScript",
    content:
      "こちらも4年になりますが、最初はバニラとjQueryばかり書いていました。最近はVue.jsばかり書いています。",
  },
  {
    title: "Python",
    content:
      "大学2年生の時にインターンで初めて触れました。主にWeb系でDjangoというフレームワークを使ってます。機械学習も勉強中です。",
  },
  {
    title: "Swift",
    content: "去年から少し勉強を始めました。ちょこっとだけかけます。",
  },
];
</script>

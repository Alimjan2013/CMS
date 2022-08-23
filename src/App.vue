<template>
  <div class="Section">
    <Title />
    <Tabs />
    <Cards />
  </div>
</template>

<script>
import Title from "./components/title.vue";
import Tabs from "./components/tabs/tabs.vue";
import Cards from "./components/cards/cards.vue";
export default {
  name: "App",
  components: {
    Title: Title,
    Tabs: Tabs,
    Cards: Cards,
  },
};
</script>

<style>
.Section {
  display: flex;
  flex-direction: column;
  align-items: stretch;
  gap: 32px;
  background: #F5F7Fa;
  padding-top: 80px;
  padding-bottom: 80px;
}
</style>

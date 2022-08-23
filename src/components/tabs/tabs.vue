<template>
  <div class="tabs">
    <Tab :isActive="true" tabName="Tab1" />
    <Tab tabName="Tab2" />
    <Tab tabName="Tab3" />
  </div>
</template>

<script>
import Tab from "./tab.vue";

export default {
  name: "App",
  components: {
    Tab: Tab,
  },
};
</script>

<style >
.tabs {
  display: flex;
  border-bottom: 1px solid #D9D9D9;
  justify-content: center;
}
</style >
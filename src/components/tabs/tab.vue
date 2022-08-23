<template>
  <div :class="['tab', { activeTab: isActive }]">{{ tabName }}</div>
</template>
<script>
export default {
  data() {
    return {
      // isActive: true,
    };
  },
  props: {
    isActive: {
      type: Boolean,
      default: false,
    },
    tabName: {
      type: String,
      default: "tab",
    },
  },

  components: {},
};
</script>
<style >
.tab {
  padding: 12px;
  font-size: 14px;
  font-weight: 400;
  line-height:22px;
  color: rgba(0, 0, 0, 0.85);
}
.activeTab {
  color: #4876FF;
  border-bottom: 1px solid #4876FF;
}
</style >
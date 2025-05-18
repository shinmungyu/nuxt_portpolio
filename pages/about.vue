<template>
  <div>
    <div>This page is about me.</div>
    <div>
      <button @click="enableCustomLayout">Update layout</button>
    </div>
  </div>
</template>
<script setup>
// definePageMeta({
//   layout: "another",
// });
function enableCustomLayout() {
  setPageLayout("another");
}
</script>
<style></style>

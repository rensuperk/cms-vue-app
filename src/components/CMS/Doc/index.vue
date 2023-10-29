<template>
  <div>
    <svg-icon icon-class="question" @click="goto" />
  </div>
</template>

<script setup>
const url = ref('http://doc.cms.vip/cms-vue');

function goto() {
  window.open(url.value)
}
</script>
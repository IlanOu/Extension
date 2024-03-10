<template>
    <input type="button" :value=value class="bg-[#e0dffd] text-[#7766C6] px-3 py-1 rounded-3xl cursor-pointer font-bold buttonShadow"/>
</template>

<script setup lang="ts">


const props = defineProps({
  value: {
    type: String,
    required: true,
  }
});

</script>

<style scoped>
    .buttonShadow {
        box-shadow: 0 5px 5px 0px rgba(224, 223, 253, 0.5);
    }
</style>
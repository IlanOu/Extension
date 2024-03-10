<template>
    <div class="rounded-xl p-3 shadow-lg divBox">
        <p class="text-[#7766C6] font-bold text-lg">
            {{title}}
        </p>
        <hr>
        <div class="text-[#7766C6]">
            <slot></slot>
        </div>
    </div>

</template>

<script setup lang="ts">


const props = defineProps({
  title: {
    type: String,
    required: true,
  }
});

</script>

<style scoped>

    hr {
        border: solid 1px #e0dffd;
    }

    .divBox{
        box-shadow: 0 10px 20px 0px rgba(224, 223, 253, 0.5);
    }

</style>
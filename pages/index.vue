<script setup lang="ts">
import { ref } from "vue";

const count: Ref<number> = ref(0);
let a: number = 10;
</script>
<template>
    test variable
    {{ a }}
    {{ count }}
</template>

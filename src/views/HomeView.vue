<script setup>
import { onMounted, ref } from 'vue'

const msg = ref()
onMounted(() => {
    msg.value = 'Hello World!'
})
</script>
<template>
    <h1>{{ msg + "!!!" }}</h1>
</template>

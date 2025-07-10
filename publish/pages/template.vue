<template>

  <h1>template</h1>
</template>


<script setup>
import { ref } from 'vue'

const selected = ref(0)

definePageMeta({ header: { contentTitle: '헤더타이틀', rightBtn: { icon: IMenu, click: () => {} } }})
definePageMeta({ layout: 'web', webHeader: { contentTitle: '헤더타이틀', rightBtn: { icon: IMenu, click: () => {} } }})
</script>


<style>

</style>
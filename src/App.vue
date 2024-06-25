<script setup>
import { RouterView } from 'vue-router';
import MemoList from '@/components/MemoList.vue';
</script>

<template>
    <h1>메모 앱</h1>
    <h1>Memo 목록</h1>
    <RouterView />
    <MemoList />
</template>

<style scoped></style>

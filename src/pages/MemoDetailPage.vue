<script setup>
import { ref, reactive } from 'vue';
import { useRoute, useRouter } from 'vue-router';
import axios from 'axios';

const BASE = '/api/memo';

// 4.	메모 상세 보기 페이지의 스크립트 코드를 완성하세요.
//   - 돌아가기 버튼을 클릭하면 목록 보기로 이동한다.

//////////////////////////////////

load(); //초기 데이터 로드 함수 호출
</script>

<template>
    <div>
        <h2>제목: {{ memo.title }}</h2>
        <hr />
        {{ memo.content }}
        <div>
            <button @click="back">돌아가기</button>
        </div>
    </div>
</template>

<style scoped></style>

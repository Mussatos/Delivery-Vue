<script setup>
const props = defineProps(["title"])


</script>

<template>
    <el-button>{{ title }}</el-button>
</template>


<style scoped>

.el-button{
    background-color: white;
    width: 100%;
    border: solid 2px #D9D0E3;
    color: #D9D0E3;
    height: 48px;
    font-weight: 400;
    font-size: 16px;
}


</style>
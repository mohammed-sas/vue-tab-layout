<template>
    <h3 class="heading" @click="$emit('current-tab',tabData.id)">{{tabData.title}}</h3>
</template>

<script>
export default {
    name:'TabHeader',
    props:{
        tabData:Object
    }
}
</script>

<style scoped>
    .heading{
        padding: 4px 12px;
        cursor: pointer;
    }
</style>
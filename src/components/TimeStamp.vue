<script setup>
    defineProps({
        tweets:{
            type: Object
        }
    })
</script>

<template>
    <span className="timestamp">{{tweets.timestamp}}</span>
</template>



<style>

</style>
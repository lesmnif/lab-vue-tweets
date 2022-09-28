<script setup>
    defineProps({
        tweets:{
            type: Object
        }
    })
</script>

<template>
    <p className="message">
        {{tweets.message}}
      </p>
</template>



<style>

</style>
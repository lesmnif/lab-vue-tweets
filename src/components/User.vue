<script setup>
    defineProps({
        tweet:{
            type: Object
        }
    })
</script>

<template>
  <div>
    <span className="user">
        <span className="name">{{tweet.user.name}}</span>
        <span className="handle">@{{tweet.user.handle}}</span>
    </span>
  </div>
</template>

<style>

</style>
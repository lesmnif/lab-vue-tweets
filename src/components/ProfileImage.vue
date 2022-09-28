<script setup>
    defineProps({
        tweets:{
            type: Object
        }
    })
</script>
<template>
  <img
      v-bind:src="tweets.user.image"
      className="profile"
      alt="Profile"
    />
</template>


<style>

</style>
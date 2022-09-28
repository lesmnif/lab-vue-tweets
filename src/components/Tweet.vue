<script setup>
import User from './User.vue';
import ProfileImage from './ProfileImage.vue';
import TimeStamp from './TimeStamp.vue';
import Message from './Message.vue';
import Actions from './Actions.vue';
  defineProps({
    tweet:{
      type: Object
    }
  })

</script>

<template>
  <div className="tweet">
    <ProfileImage
      :tweets="tweet"
    />
    <div className="body">
      <div className="top">
        <User
          :tweet="tweet"
        />
        <TimeStamp
          :tweets="tweet"
        />
      </div>

    <Message
      :tweets="tweet"
    />

    <Actions/>
    </div>

    <i class="fas fa-ellipsis-h"></i>
  </div>
</template>

<style scoped>
a {
  color: #42b983;
}
</style>

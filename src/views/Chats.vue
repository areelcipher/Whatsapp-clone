<template>
    <div>
        <app-header></app-header>
        <chat-body></chat-body>
        <new-chat></new-chat>
    </div>
</template>

<script>
import Header from '../components/Header'
import ChatBody from '../components/ChatBody'
import NewChat from '../components/NewChat'

export default {
  components: {
    'app-header': Header,
    'chat-body': ChatBody,
    'new-chat': NewChat
  }

}
</script>

<style scoped>
  div {
    margin: 0 5px 0 0;
  }
</style>
<template>
  <div id=convo-input>
    <div id="emoji-input-attach-cam">
      <i class="far fa-grin"></i>
      <input type="text" placeholder="Type a message" />
      <i class="fas fa-paperclip"></i>
      <i class="fas fa-camera"></i>
    </div>
    <div id="mic">
      <div id="microphone">
        <i class="fas fa-microphone"></i>
      </div>
    </div>
  </div>
</template>

<script>
export default {

}

</script>

<style scoped>
#convo-input {
  position: fixed;
  bottom: 0;
  display: flex;
  justify-content: space-between;
  width: 100%;
  align-items: center;
}
#emoji-input-attach-cam {
  width: 80%;
  display: flex;
  align-items: center;
  height: 52px;
  background-color: #e6e6e6;
  border-radius: 30px;
  box-sizing: border-box;
  color: grey;
}
input {
  padding: 10px;
  border: none;
  outline: none;
  background-color: #e6e6e6;
  font-size: 16px;
  width: 180px;
}
#mic {
  width: 20%;
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
}
#microphone {
  height: 50px;
  width: 50px;
  border-radius: 50%;
  background-color: #08815d;
  display: flex;
  justify-content: center;
  align-items: center;
  color: #fff;
}
.fa-grin {
  margin: 0 10px 0 10px;
}
.fa-paperclip {
  margin: 0 10px 0 -5px;
}
</style>

<template>
  <div>
    <section>
      <div id="my-status-upload">
        <div>
          <img src="./4.png" alt="" />
        </div>
        <i class="fas fa-plus-circle"></i>
      </div>
      <div id="my-status-content">
        <h3>My status</h3>
        <p>Tap to add status update</p>
      </div>
    </section>
    <p id="recent">Recent Update</p>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  margin: 10px 3px 2px 0px;
  display: flex;
  align-items: center;
}
#recent {
        padding: 5px 15px;
        margin: 0;
        background-color: #f0f0f0;
        border-top: 1px solid #bebebe;
        border-bottom: 1px solid #bebebe;
        color: #818181;
    }
#my-status-upload {
  width: auto;
  height: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 20px 0 10px;
}
#my-status-upload div {
  width: 55px;
  height: 55px;
  border-radius: 50%;
}
img {
  width: 55px;
}
#my-status-content {
  width: 85%;
}
.fa-plus-circle {
  margin-left: -20px;
  margin-top: 30px;
  font-size: 20px;
  color: green;
}
h3 {
  margin-bottom: -15px;
}
p {
  font-size: 14px;
}
</style>

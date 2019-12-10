<template>
  <div>
    <section>
      <div id="dp-caller">
        <div>
          <img src="./7.png" alt="" />
        </div>
      </div>
      <div id="call-details">
        <div id="caller">
          <h3>Hassan</h3>
          <p>December 8, 2019</p>
        </div>
        <div id="call-type">
            <i class="fas fa-video"></i>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
section {
  margin: 2px 3px 2px 0px;
  display: flex;
  align-items: center;
}
#dp-caller {
  width: auto;
  height: 70px;
  display: flex;
  justify-content: center;
  align-items: center;
  margin: 0 20px 0 10px;
}
#dp-caller div {
  width: 55px;
  height: 55px;
  border-radius: 50%;
}
img {
  width: 55px;
}
#call-details {
  width: 85%;
  border-bottom: 1px solid #bebebe;
  display: flex;
  justify-content: space-between;
  align-items: center;
  margin: 0 20px 0 5px;
}
h3 {
  margin-bottom: -15px;
}
p {
  font-size: 14px;
  color: #818181;
}
.fa-video {
    color: #08815d
}
</style>

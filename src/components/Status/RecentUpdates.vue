<template>
  <div>
    <section>
      <div id="my-status-upload">
        <div>
          <img src="./3.png" alt="" />
        </div>
      </div>
      <div id="my-status-content">
        <h3>Alvin</h3>
        <p>4 minutes ago</p>
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
    #my-status-upload {
        width: auto;
        height: 70px;
        display: flex;
        justify-content: center;
        align-items: center;
        margin: 0 20px 0 10px;
    }
    img {
      width: 55px;
    }
    #my-status-upload div {
        width: 55px;
        height: 55px;
        border-radius: 50%;
    }
    #my-status-content {
        width: 85%;
        border-bottom: 1px solid #bebebe;
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
  color: #818181;
    }
</style>

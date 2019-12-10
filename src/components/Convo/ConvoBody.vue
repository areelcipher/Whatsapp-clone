<template>
    <div>
        <div id="convo-display">
            <div class="buddy">
                <p>Hola! Hope life's fare with you</p>
            </div>
            <div class="me">
                <p>Sure, thanks for checking on me</p>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
div {
    margin: 5px 0;
    box-sizing: border-box
}
#convo-display {
    margin: 10px 0;
    width: 100%;
    height: 130px;
}
.buddy {
    float: left;
    margin: 0 0 0 10px;
    background-color: #d8d8d8;
    border-radius: 10px;
}
.me {
    float: right;
    margin: 10px 10px 0 0;
    background-color: #c3c3c3;
    border-radius: 10px;
}
p{
    padding: 0px 10px
}

</style>
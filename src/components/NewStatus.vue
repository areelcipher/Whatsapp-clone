<template>
    <div>
        <div id="pencil">
            <i class="fas fa-pen"></i>
        </div>
        <div id="cam">
            <i class="fas fa-camera"></i>
        </div>
    </div>
</template>

<script>
export default {
    
}
</script>

<style scoped>
div {
    position: fixed;
    bottom: 20px;
    right: 30px;
    display: flex;
    flex-direction: column;
    text-align: center;
}
    #pencil {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        background-color: #fff;
        z-index: 0;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
        box-shadow: 2px 3px 6px grey;
        margin: 0 4px 60px 0
    }
    #cam {
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background-color: green;
        z-index: 0;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
        box-shadow: 2px 3px 6px grey;
    }
    .fa-camera {
        color: #fff;
        font-size: 20px;
    }
</style>
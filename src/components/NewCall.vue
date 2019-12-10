<template>
    <div>
        <div id="new-call-bg">
            <i class="fas fa-phone-alt"></i>
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
    }
    #new-call-bg {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        background-color: #08815d;
        z-index: 0;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
        box-shadow: 2px 3px 6px grey;
    }
    .fa-phone-alt {
        color: #fff;
    }
</style>
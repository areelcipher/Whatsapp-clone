<template>
    <div>
        <div id="new-chat-background">
            <i class="fas fa-comment-alt fa-lg"></i>
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
    #new-chat-background {
        width: 50px;
        height: 50px;
        border-radius: 50%;
        background-color: #08815d;
        z-index: 0;
        display: flex;
        justify-content: center;
        flex-direction: column;
        align-items: center;
        box-shadow: 2px 3px 6px grey;
    }
    .fa-comment-alt {
        color: #fff;
    }
</style>
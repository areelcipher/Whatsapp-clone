<template>
    <header>
        <div id="arrow-dp-name">
            <a href="#/chats"><i class="fas fa-arrow-left"></i></a>
            <div id="dp">
                <img src="./8.png" alt="">
            </div>
            <p>Lindie</p>
        </div>
        <div id="icons">
            <i class="fas fa-video"></i>
            <i class="fas fa-phone-alt"></i>
            <i class="fas fa-ellipsis-v"></i>
        </div>
    </header>
</template>

<script>
export default {
    
}
</script>

<style scoped>
    header {
        display: flex;
        justify-content: space-between;
        align-items: center;
        background-color: #08815d;
        color: #fff;
        padding: 3px 0;
    }
    #arrow-dp-name {
        display: flex;
        align-items: center;
    }
    #icons {
        display: flex;
        justify-content: space-between;
        align-items: center;
    }
    .fa-arrow-left {
        margin: 0 5px 0 5px;
    }
    #dp {
        width: 40px;
        height: 40px;
        border-radius: 50%;
        margin: 0 10px 0 0;
    }
    .fa-ellipsis-v {
        margin: 0 10px 0 25px;
    }
    .fa-phone-alt {
        margin: 0 0px 0 25px;
    }
    img {
        width: 40px
    }
    a {
        color: #fff;
        text-decoration: none;
    }
</style>
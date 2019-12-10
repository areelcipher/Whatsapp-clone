<template>
    <div>
        <p> {{appName}} </p>
        <i class="fas fa-search"></i>
        <i class="fas fa-ellipsis-v"></i>
    </div>
</template>

<script>
export default {
    data() {
        return {
            appName: 'Whatsapp'
        }
    }
    
}
</script>

<style scoped>
    div {
        height: 60px;
        width: 100%;
        display: flex;
        justify-content: flex-end;
        align-items: center;
        color: #fff;
    }
    p {
        margin-right: auto;
        margin-left: 5px;
    }
    .fa-search {
        margin: 20px
    }
    .fa-ellipsis-v {
        margin-right: 5px
    }
</style>
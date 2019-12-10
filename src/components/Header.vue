<template>
    <header>
        <top-header></top-header>
        <bottom-header></bottom-header>
    </header>
</template>

<script>
import TopHeader from './Header/TopHeader'
import BottomHeader from './Header/BottomHeader'

export default {
    components: {
        'top-header': TopHeader,
        'bottom-header': BottomHeader
    }
}
</script>

<style scoped>
    header {
        background-color: #08815d;
        padding: 0 5px;
        box-sizing: border-box;
        box-shadow: 0px 3px 8px grey;
        position: sticky;
        top: -55px;
    }
</style>
<template>
    <div>
        <app-header></app-header>
        <new-call></new-call>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
        <call-log></call-log>
    </div>
</template>

<script>
import Header from '../components/Header'
import CallLog from '../components/CallLog'
import NewCall from '../components/NewCall'
export default {
    components: {
        'app-header': Header,
        'call-log': CallLog,
        'new-call': NewCall
    }
}
</script>

<style scoped>
    div {
        margin: 0;
    }
</style>
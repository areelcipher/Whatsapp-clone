<template>
    <div>
        <convo-header></convo-header>
        <convo-body></convo-body>
        <convo-body></convo-body>
        <convo-body></convo-body>
        <convo-body></convo-body>
        <convo-body></convo-body>
        <convo-input></convo-input>
    </div>
</template>

<script>
import ConvoHeader from '../components/Convo/ConvoHeader'
import ConvoBody from '../components/Convo/ConvoBody'
import ConvoInput from '../components/Convo/ConvoInput'
export default {
    components: {
        'convo-header': ConvoHeader,
        'convo-body': ConvoBody,
        'convo-input': ConvoInput
    }
}
</script>

<style scoped>
    
</style>
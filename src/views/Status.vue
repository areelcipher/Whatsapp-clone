<template>
    <div>
        <app-header></app-header>
        <my-status></my-status>
        <new-status></new-status>
        <recent-updates></recent-updates>
        <recent-updates></recent-updates>
        <recent-updates></recent-updates>
        <recent-updates></recent-updates>
        <recent-updates></recent-updates>
        <recent-updates></recent-updates>
        <recent-updates></recent-updates>
        <recent-updates></recent-updates>
        <recent-updates></recent-updates>
    </div>
</template>

<script>
import Header from '../components/Header'
import MyStatus from '../components/Status/MyStatus'
import RecentUpdates from '../components/Status/RecentUpdates'
import NewStatus from '../components/NewStatus'

export default {
  components: {
    'app-header': Header,
    'my-status': MyStatus,
    'recent-updates': RecentUpdates,
    'new-status': NewStatus
  }

}
</script>

<style scoped>

</style>
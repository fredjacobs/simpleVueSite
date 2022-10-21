<template>
  <div>
    <page-header />
    <first-page />
    <NuxtLogo />
  </div>
</template>

<script>
import PageHeader from '../components/PageHeader.vue'
import FirstPage from '../components/FirstPage.vue'
export default {
  name: 'IndexPage',
  components: { PageHeader, FirstPage },
  
}
</script>

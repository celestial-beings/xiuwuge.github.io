
<template>
  <Layout>
    <template #navbar-after>
      <div class="my-footer"></div>
    </template>
  </Layout>
</template>

<script>
import Layout from '@vuepress/theme-default/lib/client/layouts/Layout.vue'

export default {
  components: {
    Layout
  }
}
</script>

<style lang="css">
.my-footer {
  text-align: center;
  color: red;
}
</style>
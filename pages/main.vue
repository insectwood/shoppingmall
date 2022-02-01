<template>
  <div>
    <h1>main page</h1>
    <div>
      <ProductListPage></ProductListPage>
    </div>
  </div>
</template>

<script>
import ProductListPage from '~/components/ProductList'
export default {
  name: 'MainPage',
  components: { ProductListPage },
}
</script>

<style scoped>

</style>

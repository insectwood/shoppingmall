<template>
  <div>
    <header>
      <h1>{{ $route.name }} Page</h1>
      <nuxt-link to='/'>Home page</nuxt-link>
      <nuxt-link to='/main'>Main page</nuxt-link>
      <nuxt-link to='/product'>Product page</nuxt-link>
    </header>
    <Nuxt />
  </div>
</template>

<script>
export default {
  name: 'DefaultPage',
}
</script>

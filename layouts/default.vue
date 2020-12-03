<template>
  <div>
    <Search />
    <Navbar />
    <main>
      <div class="container">
        <Nuxt />
      </div>
    </main>

  </div>
</template>

<script>
import Navbar from '~/components/Navbar'
import Search from '~/components/Search'
export default {
  components: {
    Search
  }
}
</script>

<style>

</style>

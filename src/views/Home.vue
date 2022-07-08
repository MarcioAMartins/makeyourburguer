<template>
  <Banner />
  <div class="main-container">
    <h1>Monte o seu burger:</h1>
    <Burguerform />
  </div>
</template>

<script>
import Banner from "../components/Banner.vue"
import Burguerform from "../components/Burguerform.vue"

export default {
  name:"Home",
  components: {
    Banner,
    Burguerform
  }
}

</script>

<style scoped>

</style>
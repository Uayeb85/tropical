<template>
  <div class="layout">
    <header>
      <nav class="py-4 md:py-10">
        <Barra />
      </nav>
    </header>
    <main>
      <slot/>
    </main>
    <footer>
      <Footer />
    </footer>
  </div>
</template>

<static-query>
query {
  metadata {
    siteName
  }
}
</static-query>

<script>
import Barra from '~/components/Barra.vue'
import Footer from '~/components/Footer.vue'

export default {
  components:{
    Barra,
    Footer
  }
}
</script>


<style>



</style>
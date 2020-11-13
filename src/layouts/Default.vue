<template>
  <div class="layout fondo">
    <header>
      <nav class="py-4 md:py-10">
        <Barra />
      </nav>
    </header>
    <main>
      <slot/>
    </main>

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

export default {
  components:{
    Barra,
  }
}
</script>


<style>

*{
  margin: 0;
  box-sizing: border-box
}

.fondo{
    background:#f0e5d8;
}

</style>
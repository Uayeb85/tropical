<template>
  <Layout class="fondo">
      <section class="text-gray-700 body-font total no">
        <div class="container-fluid px-5 pt-3 md:pt-0 mx-auto">
          <div class="flex justify-center items-center flex-wrap -m-4">
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                <g-image src="~/img/cuchillo.svg" class="ml-12  md:mt-0 md:pt-40 md:ml-32" />
            </div>           
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                <g-image src="~/img/pescado.svg" class="ml-40 md:ml-12 pb-20" />

              <div class="ml-10 md:pt-10">
                <g-image src="~/img/manzana.svg" class="ml-20 md:mt-8" />
              </div>
            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
                    <g-image src="~/img/flecha.svg" class="ml-8 pt-10 " />


              <div class="mt:0 md:mt-4">
                  <g-image src="~/img/monito.svg" class="pt:0 md:pt-24 size" />
              </div>
            </div>
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                  <g-image src="~/img/calaca.svg" class="pt-0 ml-48 md:ml-0 md:pb-10" />

              <div class="mt-0 md:mt-4">
                  <g-image src="~/img/reloj.svg" class="pt-0 -mt-24 ml-8 md:pt-32 md:ml-32" />

              </div>
            </div>
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                  <g-image src="~/img/cuaderno.svg" class="-ml-32 mb-56 " />

            </div>
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                <g-image src="~/img/vibora.svg" class="md:ml-24 md:mb-64" />
            </div>
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">               
                <g-image src="~/img/florero.svg" class="ml-24 -mt-10 md:ml-32 md:mb-40 " />
            </div>
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                <g-image src="~/img/bug.svg" class="ml-32 mb-64   " />
            </div>
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                  <g-image src="~/img/flor.svg" class="mb-64 ml-32 " />
            </div>
          </div>
        </div>
      </section>

      <section class="no-mobile">
        <Imagenes />
      </section>

      <section>
        <Proyecto id="editorial" />
      </section>

      <section>
        <Esplin id="esplin" />
      </section>
      <section>

        <Contacto id="contacto" />
      </section>
      <footer>

         <Footer class="foot" />
      </footer>

  </Layout>
</template>

<script>
import Imagenes from '~/components/Imagenes.vue'
import Proyecto from '~/components/Proyecto.vue'
import Esplin from '~/components/Esplin.vue'
import Contacto from '~/components/Contacto.vue'
import Footer from '~/components/Footer.vue'


export default {
  components:{
    Imagenes,
    Footer,
    Esplin,
    Contacto,
    Proyecto
  },
  metaInfo: {
    title: 'Esplin Tropical'
  }
}
</script>

<style>
@media only screen and (min-width: 0px)  and (max-width: 768px){

.fondo{
  background: #fcf2eb ;
}


.no{
  display: none;
}

.size{
  width: 350px;
  height: 150px;
}

}

@media only screen and (min-width: 769px)  and (max-width: 2900px) {


.fondo{
  background:#fcf2eb ;
}

  .total{
  height: 750px;
  width: auto;
}

.size{
  width: 450px;
  height: 350px;
}

.no-mobile{
  display: none;
}

}

</style>

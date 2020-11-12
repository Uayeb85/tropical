<template>
  <Layout class="fondo">
      <section class="text-gray-700 body-font total">
        <div class="container px-5 pt-3 md:py-32  mx-auto">
          <div class="flex  flex-wrap -m-4">
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                <g-image src="~/img/flecha.svg" class="ml-12 md:pt-24 md:ml:0" />
            </div>           
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                <g-image src="~/img/calaca.svg" class="ml-40 md:ml-24 pt-10" />

              <div class="ml-10 md:pt-32">
                <g-image src="~/img/bug.svg" class="" />
              </div>
            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
                    <g-image src="~/img/cuchillo.svg" class="ml-32 pt-10 no" />

              <div class="mt:0 md:mt-4">
                  <g-image src="~/img/monito.svg" class="pt:0 md:pt-24 size" />
              </div>
            </div>
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                  <g-image src="~/img/pescado.svg" class="pt-0 ml-48 md:ml-0 md:pt-24" />

              <div class="mt-0 md:mt-4">
                  <g-image src="~/img/cuaderno.svg" class="pt-0 -mt-24 ml-8 md:pt-24 md:ml-40" />

              </div>
            </div>
            <div class="lg:w-1/6 md:w-1/2 p-4 w-full">
                  <g-image src="~/img/manzana.svg" class="pt-20 ml-32 no" />

            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
                <g-image src="~/img/flor.svg"  />
            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
                <g-image src="~/img/vibora.svg" class="ml-24 -mt-10 md:ml-10 md:pt-10 " />
            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
                <g-image src="~/img/florero.svg" class="ml-20 pt-10 no " />
            </div>
            <div class="lg:w-1/4 md:w-1/2 p-4 w-full">
                  <g-image src="~/img/reloj.svg" class="pt-20 ml-32 no" />
            </div>
          </div>
        </div>
      </section>
  </Layout>
</template>

<script>
export default {
  metaInfo: {
    title: 'Esplin Tropical'
  }
}
</script>

<style>
@media only screen and (min-width: 0px)  and (max-width: 768px){

.fondo{
  background:#f0e5d8 ;
}

.total{
  width: auto;
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
  background:#f0e5d8 ;
}

  .total{
  height: auto;
  width: auto;
}
}

</style>

<template>
    <section class="text-gray-700 body-font total">
        <div class="container-fluid px-5 pt-3 pb-10 md:pt-0 mx-auto">
          <div class="flex justify-center items-center flex-wrap -m-4">
            <div class="w-1/4   ">
                <g-image src="~/img/pescado.svg" class="ml-10" />
            </div>

            <div class="w-1/4 mt-20">
                <g-image src="~/img/cuchillo.svg" class="mt-8" />
            </div>
          

            <div class="w-1/4 mb-10">
                <g-image src="~/img/flecha.svg" class="" />
              </div>
            <div class="w-1/4 mb-10">
                    <g-image src="~/img/cuaderno.svg" class="ml-10  " />

            </div>
            <div class="">
                  <g-image src="~/img/calaca.svg" class=" ml-64" />
            </div>
            <div class="">
                  <g-image src="~/img/reloj.svg" class="mt-4 ml-32" />

            </div>
            <div class="w-full">
                  <g-image src="~/img/manzana.svg" class="ml-16 " />

            </div>

   
            <div class="w-1/4 absolute">               
                <g-image src="~/img/flor.svg" class="ml-64 mt-64" />
            </div>

            <div class="w-1/2 absolute mt-20 ">
                  <g-image src="~/img/bug.svg" class="ml-56 mt-64" />
            </div>

              <div class="size">
                  <g-image src="~/img/monito.svg" class="-mt-10" />
              </div>




            <div class="w-full">               
                <g-image src="~/img/vibora.svg" class="ml-32 -mt-16" />
            </div>
            <div class="w-full">
                <g-image src="~/img/florero.svg" class="ml-64" />
            </div>

          </div>
        </div>
      </section>
</template>

<script>
export default {
    name:'Imagenesipad',
}
</script>

<style scoped>

.total{
  height: auto;
}

.size{
  width: 250px;
  height: 170px;
}

</style>
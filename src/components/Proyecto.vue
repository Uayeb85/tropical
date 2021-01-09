<template>
    <section class="text-gray-700 body-font overflow-hidden fondo12">
        <div class="container px-5 py-24 mx-auto">
            <div class="lg:w-4/5 mx-auto flex flex-wrap">
            <div class="flex justify-center items-center">
            <g-image alt="ecommerce" class="imagen flex ml-32 md:ml-0 md:object-center md:object-contain md:flex md:items-center md:justify-center " src="~/img/manzana-blanca.svg" />
            </div>

            <div class="lg:w-1/3 w-full lg:py-6 mt-6 lg:mt-0 ml-0 md:ml-10">
                <p class="leading-relaxed pb-4 color-font">Esplín tropical es un proyecto editorial, a pequeña escala, imaginado y gestado en la Ciudad de México. Hacemos libros inspirados por el ejercicio del aburrimiento. </p>
                <p class="leading-relaxed pb-4 color-font">Walter Benjamín escribió, quien no se aburre, no tiene la capacidad de contar historias. Tanto para quien narra historias, como para quien las escucha, el aburrimiento es un padecimiento vital. Éste, no refiere a un estado de inacción, más bien, a uno de profunda introspección: un viaje a las profundidades del yo. </p>
                <p class="leading-relaxed color-font">Buscamos historias en el impasse cotidiano, en las caminatas sin trayectoria aparente y en las redundancias temporales del ser. Construimos una biblioteca como un refugio de voces y miradas que consideramos imprescindibles, relevantes a nuestro tiempo y, sobre todo, necesarias para recuperar el aliento.  </p>
            </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'Proyecto',
}
</script>

<style  scoped>


.fondo12{
    background: #293b5c
}

.imagen{
    height: 50px;
    width: 50px;
}

.color-font{
    color: #fcf2eb;
}

</style>
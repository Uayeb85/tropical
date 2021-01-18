<template>
    <section class="text-gray-700 body-font overflow-hidden fondo12">
        <div class="container px-5 py-10 mx-auto">
            <div class="lg:w-4/5 mx-auto md:flex md:flex-wrap">
                <div class="flex justify-center md:items-center">
                    <g-image alt="manzana-blanca" class="imagen" src="~/img/manzana-blanca.svg" />

                </div>

                <div class="lg:w-1/3 w-full lg:py-6 mt-6 lg:mt-0 ml-0 md:ml-16">
                    <p class="leading-relaxed pb-4 color-font">Esplín tropical es un proyecto editorial, a pequeña escala, imaginado y gestado en la Ciudad de México. <span class="font-bold"> Hacemos libros inspirados por el ejercicio del aburrimiento. </span>   </p>
                    <p class="leading-relaxed pb-4 color-font">Walter Benjamín escribió, quien no se aburre, no tiene la capacidad de contar historias. Tanto para los procesos
                        de escritura como para los hábitos de lectura, el aburrimiento se asoma como un padecimiento necesario. No
                        sólo refiere - como tanto se piensa - a un estado superficial de inacción y pasividad, sino alude a uno de profunda
                        movilidad: un viaje por las geografías de la memoria, la imaginación y las propias nociones del <span class="italic" >yo </span> . </p>
                    <p class="leading-relaxed color-font">Buscamos historias en ese impasse cotidiano, en las caminatas sin trayectoria aparente y en las redundancias del
                        ser. Construimos una biblioteca como un refugio de voces y miradas que consideramos imprescindibles,
                        relevantes a nuestro tiempo y, sobre todo, necesarias para hacer una pausa, y recuperar el aliento.  </p>
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

.direccion{
    display: flex;
    align-items: center;
    justify-content: center;
}

.imagen{
    height: 35px;
    width: 35px;
    
}

.color-font{
    color: #fcf2eb;
}

</style>
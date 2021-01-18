<template>
    <section class="text-gray-700 body-font overflow-hidden fondo12">
        <div class="container px-5 py-10 mx-auto">
            <div class="lg:w-4/5 mx-auto flex flex-wrap">

            <div class="lg:w-1/3 w-full  lg:py-6 mt-6 lg:mt-0 ml-0 md:ml-24 no-des">
                <p class="leading-relaxed pb-4 letra"> Pautas para la recepción de obra original:  </p>
                <p class="leading-relaxed  letra italic"> *Currículum Vitae </p>
                <p class="leading-relaxed  letra italic"> *Sinopsis del argumento  </p>
                <p class="leading-relaxed  letra italic"> *No. de páginas  </p>
                <p class="leading-relaxed  letra italic"> *Obra (no se tomará en consideración una obra incompleta)  </p>


            </div>

            <div class="lg:w-1/3 w-full lg:py-6 mt-6 lg:mt-0 ml-0 md:ml-24 no">
                <p class="leading-relaxed pb-4 letra">Para más información sobre nuestra línea editorial y las pautas para recibir obra original:  </p>
                <a href="mailto:ediciones@esplintropical.com "> <p class="leading-relaxed pb-4 letra italic">ediciones@esplintropical.com  </p> </a> 

            </div>

            <div class=" mt-10 md:mt-0 flex  justify-center items-center">
                <g-image alt="pescado" class="imagen object-center object-contain flex items-center justify-center " src="~/img/pescado-blanco.svg" />
            </div>


            <div class="lg:w-1/3 w-full lg:py-6 mt-6 lg:mt-0 ml-0 md:ml-24 no-des">
                <p class="leading-relaxed pb-4 letra">Para más información sobre nuestra línea editorial y las pautas para recibir obra original:  </p>
                <a href="mailto:ediciones@esplintropical.com "> <p class="leading-relaxed pb-4 letra italic">ediciones@esplintropical.com  </p> </a> 

            </div>

            <div class="lg:w-1/3 w-full  lg:py-6 mt-6 lg:mt-0 ml-0 md:ml-24 no">
                <p class="leading-relaxed pb-4 letra"> Pautas para la recepción de obra original:  </p>
                <p class="leading-relaxed  letra italic"> *Currículum Vitae </p>
                <p class="leading-relaxed  letra italic"> *Sinopsis del argumento  </p>
                <p class="leading-relaxed  letra italic"> *No. de páginas  </p>
                <p class="leading-relaxed  letra italic"> *Obra (no se tomará en consideración una obra incompleta)  </p>


            </div>

            </div>

        </div>
    </section>
</template>

<script>
export default {
    name:'Contacto',
}
</script>

<style  scoped>


@media only screen and (min-width: 0px)  and (max-width: 768px){

.fondo12{
    background: #293b5c;
}

.imagen{
    height: 50px;
    width: 50px;
}

.letra{
    color: #fcf2eb;
}

.no{
    display: none;
}

}


@media only screen and (min-width: 769px)  and (max-width: 2900px) {

.fondo12{
    background: #293b5c;
}

.imagen{
    height: 50px;
    width: 50px;
}

.letra{
    color: #fcf2eb;
}

.no-des{
    display: none;
}

}





</style>
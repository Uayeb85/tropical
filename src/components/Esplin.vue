<template>
    <section class="text-gray-700 body-font overflow-hidden fondo12">
        <div class="container px-5 py-10 mx-auto">
            <div class="lg:w-4/5 mx-auto md:flex md:flex-wrap md:justify-center lg:justify-start">
                <div class="flex justify-center md:items-center no-des">
                    <g-image alt="flor" class="imagen  flex items-center justify-center " src="~/img/flor.svg" />
                </div>
                <div class="lg:w-1/3 w-full md:px-6 lg:px-0 lg:py-6 mt-6 lg:mt-0 ml-0 md:ml-0 lg:ml-24 md:text-justify lg:text-left">
                    <p class="leading-relaxed pb-4 letra">La palabra <span class="italic"> spleen </span>  tiene un origen en la medicina antigua y hace referencia al bazo (splên), órgano que, acorde
                        a la teoría de Hipócrates, se encargaba de nivelar los humores del cuerpo. Un exceso de bilis negra, resultado de
                        una mala combinación, sumergía a quién la padecía en un estado
                        de abatimiento y melancolía.  
                        Aristóteles relacionaba la experiencia melancólica con la enfermedad, pero de igual manera, con el genio y la
                        excepcionalidad. Para Baudelaire, el esplín suponía una aflicción vital sin causa aparente: una experiencia
                        simultánea de hartazgo y vacío. Para ambos, el sujeto melancólico se encontraba <span class="italic">fuera de sí, </span>  es decir, sometido a
                        una voluntad ajena y convertido en objeto de sus propios actos.
                    </p>
                </div>
                <div class="lg:w-1/3 w-full md:px-6 lg:px-0  lg:py-6 mt-6 lg:mt-0 ml-0 md:ml-0 lg:ml-16 md:text-justify lg:text-left flex justify-center items-center">
                    <p class="leading-relaxed pb-4 letra"> <span class="font-bold"> ¿Cómo entender los actos de narrar y escuchar historias sin esta experiencia de <span class="italic">  desdoblamiento, </span> de viaje, de alteridades y otredades?  </span> 
                         En Esplín Tropical buscamos diseñar una cartografía imaginativa inspirada por estas visiones y
                        padecimientos. Una biblioteca indispensable para todos aquellos lectores que estén interesados en un refugio
                        bajo nuestro mal de ánimo tropical.
                    </p>
                </div>
                <div class="flex justify-center items-center  md:mt-0  md:ml-16 no ">
                        <g-image alt="flor" class="imagen flex items-center justify-center " src="~/img/flor.svg" />
                </div>
            </div>
        </div>
    </section>
</template>

<script>
export default {
    name:'Esplin',
}
</script>

<style  scoped>
 
@media only screen and (min-width: 0px)  and (max-width: 600px){
.fondo12{
    background: #fcf2eb;
}
.imagen{
    height: 50px;
    width: 50px;
}
.letra{
    color: #293b5c;
}
.no{
    display: none;
}
}

@media only screen and (min-width: 601px)  and (max-width: 768px){
.fondo12{
    background: #fcf2eb;
}
.imagen{
    height: 50px;
    width: 50px;
}
.letra{
    color: #293b5c;
}
.no{
    display: none;
}
}

@media only screen and (min-width: 769px)  and (max-width: 2900px) {
.fondo12{
    background: #fcf2eb;
}
.imagen{
    height: 50px;
    width: 50px;
}
.letra{
    color: #293b5c;
}
.no-des{
    display: none;
}
}
</style>
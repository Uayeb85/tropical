<template>
        <div class="pb-5 fondo">

                <div class="flex justify-center items-center md:flex md:flex-wrap md:items-center md:justify-start md:px-12 pt-5">
                    <a href="#editorial"  class="mr-4">
                        <g-image src="~/img/acerca-footer.svg"  />
                    </a>

                    <a href="mailto:ediciones@esplintropical.com" class="mr-4">
                        <g-image src="~/img/contacto-footer.svg" />
                    </a>
                    <g-link class="mr-4">
                        <g-image src="~/img/instagram-footer.svg"  />
                    </g-link>
                    <g-link class="mr-4">
                        <g-image src="~/img/twitter-footer.svg" />
                    </g-link>
                    <g-link>
                        <g-image src="~/img/facebook-footer.svg" />
                    </g-link>
                </div>
        </div>
</template>

<script>
export default {
    name:'Footer',
}
</script>

<style scoped>

@media only screen and (min-width: 0px)  and (max-width: 768px){


.fondo{
    background:#fcf2eb;
}

}

@media only screen and (min-width: 769px)  and (max-width: 2900px) {


.fondo{
    background:#fcf2eb;
}

}



</style>
<template>
        <div class="pb-10 fondo">

                <div class="flex flex-wrap items-center px-12 pt-6">
                    <g-link class="mr-4 pb-10 md:pb-0">
                        <g-image src="~/img/acerca-footer.svg"  />
                    </g-link>
                    <a href="mailto:ediciones@esplintropical.com" class="mr-4">
                        <g-image src="~/img/contacto-footer.svg" />
                    </a>
                    <g-link class="mr-4">
                        <g-image src="~/img/instagram-footer.svg" />
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
<template>
        <div class="pt-10 pb-10 fondo">

                <div class="flex justify-center items-center md:flex md:flex-wrap md:items-center md:justify-start md:px-12 ">
                    <a href="#editorial"  class="mr-4">
                        <g-image src="~/img/acerca-footer.svg"  />
                    </a>

                    <a href="mailto:ediciones@esplintropical.com" class="mr-4">
                        <g-image src="~/img/contacto-footer.svg" />
                    </a>

                    <a href="https://www.instagram.com/esplintropicaled" class="mr-4">
                        <g-image src="~/img/instagram-footer.svg"  />
                    </a>

                    <a href="https://twitter.com/esplintropical" class="mr-4">
                        <g-image src="~/img/twitter-footer.svg" />
                    </a>
                    
                    <a href="https://www.facebook.com/esplintropicaled">
                        <g-image src="~/img/facebook-footer.svg" />
                    </a>
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
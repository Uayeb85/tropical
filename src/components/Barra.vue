<template>
<div class="barra">
<header class="sm:flex sm:justify-between sm:items-center sm:px-4 sm:py-4  fondo ">
      <div class="flex items-center justify-between px-4 py-4 sm:p-0">
        <div class="px-0 md:px-8">
            <g-link to="/">
             <g-image src="~/img/logo.svg" class="" />
            </g-link>
        </div>
        <div class="sm:hidden">
            <button @click="isOpen = !isOpen"  type="button" class=" block color focus:color focus:outline-none ">
                <svg class="h-4 fill-current"  viewBox="0 0 510 510">
                    <path v-if="isOpen" fill-rule="evenodd" d="M505.922,476.567L285.355,256L505.92,35.435c8.106-8.105,8.106-21.248,0-29.354c-8.105-8.106-21.248-8.106-29.354,0L256.001,226.646L35.434,6.081c-8.105-8.106-21.248-8.106-29.354,0c-8.106,8.105-8.106,21.248,0,29.354L226.646,256L6.08,476.567c-8.106,8.106-8.106,21.248,0,29.354c8.105,8.105,21.248,8.106,29.354,0l220.567-220.567l220.567,220.567c8.105,8.105,21.248,8.106,29.354,0S514.028,484.673,505.922,476.567z"/>
                    <path v-if="!isOpen" fill-rule="evenodd" d="M505.755,123.592c-8.341-8.341-21.824-8.341-30.165,0L256.005,343.176L36.421,123.592c-8.341-8.341-21.824-8.341-30.165,0s-8.341,21.824,0,30.165l234.667,234.667c4.16,4.16,9.621,6.251,15.083,6.251c5.462,0,10.923-2.091,15.083-6.251l234.667-234.667C514.096,145.416,514.096,131.933,505.755,123.592z"/>
                </svg>
            </button>
        </div>
      </div>
      <div :class="isOpen ? 'block' : 'hidden'" class="px-4 pt-2 pb-4 sm:flex sm:p-0"  >
          <div class="px-0 md:px-8 flex flex-col items-end ">
             <a href="#editorial"> <g-image src="~/img/acerca.svg" class="pb-4" /></a> 
             <a href="#esplin"> <g-image src="~/img/esplin.svg" class="pb-4" /></a> 
             <a href="#contacto"><g-image src="~/img/contacto.svg" /></a> 
          </div>
      </div>  
  </header>
  <div class="px-12"> 
    <hr class="color-linea">

  </div>
</div>
  
</template>

<script>
export default {
    name:'Barra',
    data(){
        return{
            isOpen:false,
            estaAbierto:false,
        }
    }
}
</script>


<style scoped>

@media only screen and (min-width: 0px)  and (max-width: 768px){

.barra{
    overflow: hidden;
    position: fixed;
    top: 0;
    width: 100%;
}

.fondo{
  background: #fcf2eb;
}

.color{
    color:#293b5c;
}

.color-linea{
    background-color: #293b5c;
    width: 100%;
    height: 1px;
}

.no{
  display: none;
}

}

@media only screen and (min-width: 769px)  and (max-width: 2900px) {


.barra{
    overflow: hidden;
    position: fixed;
    top: 0;
    width: 100%;
}


.fondo{
  background: #fcf2eb;
}


.color{
    color:#293b5c;
}

.color-linea{
    background-color: #293b5c;
    width: 100%;
    height: 1.5px;
    text-align: center;
}


}




</style>
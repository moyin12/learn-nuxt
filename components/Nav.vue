<template> 
    <nav class="flex justify-between w-auto bg-black bg-opacity-27 p-4 md:p-8">
        <nuxt-link to="/" class="text-white">
            Moyin Ariyo
        </nuxt-link>
        <button class="block md:hidden cursor-pointer">
            <font-awesome-icon class="text-white" :icon="['fas' , 'bars']" />
        </button>
        <div class=" w-6/12 hidden md:block">
            <ul class="flex">
                <li class="flex-1 text-white">
                    <nuxt-link class="" to="/">
                        Home
                    </nuxt-link>
                </li>
                <li class="flex-1 text-white">
                    <nuxt-link to="services">
                        Services
                    </nuxt-link>
                </li>
                <li class="flex-1 text-white">
                    <nuxt-link to="about">
                        About 
                    </nuxt-link>
                </li>
                <li class="flex-1 text-white">
                    <nuxt-link to="blogs">
                        Blogs 
                    </nuxt-link>
                </li>
                <li class="flex-1 text-white">
                    <nuxt-link to="contact">
                        Contact
                    </nuxt-link>
                </li>
            </ul>   
        </div>
        <div class="hidden md:block">
            <ul class="flex justify-between w-24">
                <li>
                    <a href="https://twitter.com/ariyo_moyin" target="_blank" rel="noopener noreferrer">
                        <span class="icon"> 
                            <font-awesome-icon class="text-white" :icon="['fab' , 'twitter']" />
                        </span>
                    </a>
                </li>
                <li>
                    <a href="https://www.behance.net/" target="_blank" rel="noopener noreferrer">
                        <span class="icon"> 
                            <font-awesome-icon class="text-white" :icon="['fab' , 'behance']" />
                        </span>
                    </a>
                </li>
                <li> 
                    <a href="https://www.linkedin.com/in/moyinoluwa-ariyo-641a97165/" target="_blank" rel="noopener noreferrer">
                        <span class="icon"> 
                            <font-awesome-icon class="text-white" :icon="['fab' , 'linkedin-in']" />
                        </span>
                    </a>
                </li>
            </ul>
        </div>
    </nav>
   
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>
<template> 
    <header class="flex justify-between w-auto bg-black bg-opacity-27 p-4 md:p-8">
        <nuxt-link to="/" class="text-white">
            Moyin Ariyo
        </nuxt-link>
        <!-- <span class="icon">
            <font-awesome-icon class="text-white" :icon="['fa' , 'bars']" />
        </span> -->
        <nav class=" w-6/12 hidden md:block">
            <ul class="flex">
                <li class="flex-1 text-white">
                    <nuxt-link class="hover:border-b-2 hover:border-white hover:pb-4" to="/">
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
        </nav>
        <div class="hidden md:block">
            <ul class="flex justify-between w-24">
                <li>
                    <nuxt-link to="contact">
                        <span class="icon"> 
                            <font-awesome-icon class="text-white" :icon="['fab' , 'twitter']" />
                        </span>
                    </nuxt-link>
                </li>
                <li>
                    <nuxt-link to="behance">
                        <span class="icon"> 
                            <font-awesome-icon class="text-white" :icon="['fab' , 'behance']" />
                        </span>
                    </nuxt-link>
                </li>
                <li> 
                    <nuxt-link to="behance">
                        <span class="icon"> 
                            <font-awesome-icon class="text-white" :icon="['fab' , 'linkedin-in']" />
                        </span>
                    </nuxt-link>
                </li>
            </ul>
        </div>
    </header>
   
</template>

<script>
export default {
    
}
</script>

<style scoped>

</style>
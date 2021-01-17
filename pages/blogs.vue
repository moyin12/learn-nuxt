<template>
  <div class="font-sans">
    <Nav />
    <ul class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8 md:gap-12 p-8 max-w-screen-lg m-auto">
      <li class="rounded-md shadow-lg" v-for="post in posts" :key="post.id">
        <img class="rounded-t-md h-48 w-full" :src="post.image" />
        <div class="px-4 pb-4">
          <h4 class="font-bold text-lg">{{ post.title }}</h4>
          <p class="overflow-ellipsis  overflow-hidden h-48">{{ post.description }}</p>
        </div>
      </li>
    </ul>
  </div>
</template>

<script>
import axios from 'axios'
export default {
    data: function () {
    return {
      posts: [],
    };
  }, 

   fetch: function (){
       axios
       .get('https://api.nuxtjs.dev/posts')
       .then((res) => {
          this.posts = res.data
       })
       .catch((err) => {
        console.log(err);
      });
   }
}
</script>

<style scoped>

</style>
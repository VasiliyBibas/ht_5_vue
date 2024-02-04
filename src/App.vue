<template>
  <Main/>
  <Blog/>
  <BlogDetails/>
  <ProductDetails/>

</template>

<script>
import Main from './components/Main.vue';
import Blog from './components/Blog.vue';
import BlogDetails from './components/BlogDetails.vue';
import ProductDetails from './components/ProductDetails.vue';



export default {
  name: 'App',
  components: {
    Main,
    Blog,
    BlogDetails,
    ProductDetails
}
}
</script>

<style lang="scss">

</style>

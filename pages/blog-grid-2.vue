<template>
  <div>
    <HeaderOne />
    <PageBanner banner-title="Blog Grid" page-title="Blog Grid 2" />
    <BlogTwo />
    <Footer />
  </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import BlogTwo from "~/components/Pages/BlogTwo";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "blog-grid-2",
      components: {
        Footer,
        BlogTwo,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'Blog Grid 2 | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

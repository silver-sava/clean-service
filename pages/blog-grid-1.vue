<template>
    <div>
      <HeaderOne />
      <PageBanner banner-title="Blog" page-title="Blog Grid" />
      <BlogSidebar />
      <Footer />

    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import BlogSidebar from "~/components/Pages/BlogSidebar";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "blog-grid-1",
      components: {
        Footer,
        BlogSidebar,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'Blog Grid 1 | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

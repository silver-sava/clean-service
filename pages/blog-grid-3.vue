<template>
    <div>
      <HeaderOne/>
      <PageBanner page-title="Blog Grid 3" banner-title="Blog Grid" />
      <BlogThree />
      <Footer />

    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import BlogThree from "~/components/Pages/BlogThree";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "blog-grid-3",
      components: {
        Footer,
        BlogThree,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'Blog Grid 3 | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

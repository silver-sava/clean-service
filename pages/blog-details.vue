<template>
    <div>
      <HeaderOne />
      <PageBanner page-title="Blog Details" banner-title="Blog Details" />
      <BlogDetails />
      <Footer />

    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import BlogDetails from "~/components/Pages/BlogDetails";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "blog-details",
      components: {
        Footer,
        BlogDetails,
          PageBanner,
        HeaderOne
        },
      head(){
        return{
          title: 'Blog Details | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

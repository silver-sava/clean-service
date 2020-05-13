<template>
    <div>
      <HeaderOne />
      <PageBanner pageTitle="Error" bannerTitle="Error"/>
      <NotFound />
      <Footer />
    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import NotFound from "~/components/Pages/NotFound";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "error",
      components: {
        Footer,
        NotFound,
          PageBanner,
        HeaderOne
        },
      head(){
        return{
          title: 'Error | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

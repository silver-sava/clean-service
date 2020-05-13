<template>
    <div>
      <HeaderOne />
      <PageBanner pageTitle="Services Details" bannerTitle="Services Details" />
      <SingleService />
      <Footer />
    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import SingleService from "~/components/Pages/SingleService";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "single-service",
      components: {
        Footer,
        SingleService,
          PageBanner,
        HeaderOne
        },
      head(){
        return{
          title: 'Single Project | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

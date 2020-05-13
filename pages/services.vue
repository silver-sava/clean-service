<template>
    <div>
      <HeaderOne />
      <PageBanner page-title="Services" bannerTitle="All Services"/>
      <Welcome />
      <Services />
      <Pricing />
      <Footer />
    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import Welcome from "~/components/HomeOne/Welcome";
    import Pricing from "~/components/HomeOne/Pricing";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "services",
      components: {
        Footer,
        Pricing,
          Welcome,
        PageBanner,
        HeaderOne
        },
      head(){
        return{
          title: 'Services | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

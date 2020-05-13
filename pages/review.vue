<template>
    <div>
      <HeaderOne />
      <PageBanner pageTitle="Clients Reviews" bannerTitle="Reviews"/>
      <TestimonialsTwo />
      <Footer />
    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import TestimonialsTwo from "~/components/Pages/TestimonialsTwo";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "review",
      components: {
        Footer,
        TestimonialsTwo,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'Reviews | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

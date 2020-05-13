<template>
    <div>
      <HeaderOne />
      <PageBanner pageTitle="FAQ" bannerTitle="FAQ"/>
      <FaqAccordion />
      <Footer/>

    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import FaqAccordion from "~/components/Pages/FaqAccordion";
    import PageBanner from "~/components/Pages/PageBanner";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "faq",
      components: {
        Footer,
        FaqAccordion,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'FAQ | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

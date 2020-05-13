<template>
    <div>
      <HeaderOne />
      <PageBanner pageTitle="Our Team" bannerTitle="team"/>
      <TeamMembar />

      <Footer />
    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import TeamMembar from "~/components/Pages/TeamMembar";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "team",
      components: {
        Footer,
        TeamMembar,
        PageBanner,
        HeaderOne
        },
      head(){
        return{
          title: 'Team | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

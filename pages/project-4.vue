<template>
    <div>
      <HeaderOne />
      <PageBanner pageTitle="Project 4 " bannerTitle="Project"/>
      <Project />
      <Footer />
    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import Project from "~/components/HomeOne/Project";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "project-4",
      components: {
        Footer,
        Project,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'Project 4 | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

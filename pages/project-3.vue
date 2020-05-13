<template>
    <div>
      <HeaderOne />
      <PageBanner page-title="Project 3 " banner-title="Project" />
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
        name: "project-3",
      components: {
        Footer,
        Project,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'Project 3 | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

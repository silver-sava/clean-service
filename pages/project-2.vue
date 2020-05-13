<template>
    <div>
      <HeaderOne />
      <PageBanner page-title="Project 2 " banner-title="Project" />
      <ProjectTwo />
      <Footer />

    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import ProjectTwo from "~/components/Pages/ProjectTwo";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "project-2",
      components: {
        Footer,
        ProjectTwo,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'Project 2 | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

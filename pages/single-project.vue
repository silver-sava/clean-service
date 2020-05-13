<template>
    <div>
      <HeaderOne />
      <PageBanner page-title="Project Details" banner-title="Project" />
      <ProjectDetails />
      <RelatedProjects />
      <Footer />
    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import ProjectDetails from "~/components/Pages/ProjectDetails";
    import RelatedProjects from "~/components/Pages/RelatedProjects";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "single-project",
      components: {
        Footer,
        RelatedProjects,
        ProjectDetails,
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

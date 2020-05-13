<template>
  <div>
    <HeaderOne />
    <PageBanner pageTitle="About Us" bannerTitle="About Us"/>
    <About />
    <AboutFeature />
    <Team />
    <Testimonials />
    <Video />
    <Footer />

  </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import About from "~/components/Pages/About";
    import AboutFeature from "~/components/Pages/AboutFeature";
    import Team from "~/components/Pages/Team";
    import Testimonials from "~/components/Pages/Testimonials";
    import Video from "~/components/Pages/Video";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "about",
      components: {
        Footer,
        Video,
        Testimonials,
        Team,
        AboutFeature,
        About,
        PageBanner,
        HeaderOne
        },
      head(){
        return{
          title: 'About Us | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

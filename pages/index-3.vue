<template>
    <div>
      <HeaderThree />
      <Slider />
      <About />
      <Welcome />
      <Service />
      <Quote />
      <Blog />
      <Cta />
      <Choose />
      <Project />
      <Counter />
      <Pricing />
      <Client />
      <Footer />
    </div>
</template>

<script>
    import HeaderThree from "~/components/HomeThree/HeaderThree";
    import Slider from "~/components/HomeThree/Slider";
    import Welcome from "~/components/HomeOne/Welcome";
    import About from "~/components/HomeOne/About";
    import Service from "~/components/HomeOne/Service";
    import Quote from "~/components/HomeOne/Quote";
    import Pricing from "~/components/HomeOne/Pricing";
    import Choose from "~/components/HomeOne/Choose";
    import Project from "~/components/HomeOne/Project";
    import Counter from "~/components/HomeOne/Counter";
    import Blog from "~/components/HomeOne/Blog";
    import Footer from "~/components/HomeOne/Footer";
    import Cta from "~/components/HomeOne/Cta";
    import Client from "~/components/HomeOne/Client";

    export default {
        name: "index-3",
      components: {
        Client,
        Cta,
        Footer,
        Blog,
        Counter,
        Project,
        Choose,
        Pricing,
        Quote,
        Service,
        About,
        Welcome,
        Slider,
        HeaderThree
        },
      head(){
        return{
          title: 'Home 3 | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

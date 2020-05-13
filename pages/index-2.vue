<template>
  <div>
    <HeaderOne />
    <MainBanner />
    <WelcomeTwo />
    <About />
    <Service />
    <Quote />
    <Blog />
    <Choose />
    <Project />
    <Counter />
    <Pricing />
    <Client />
    <Footer />
  </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import MainBanner from "~/components/HomeTwo/MainBanner";
    import WelcomeTwo from "~/components/HomeTwo/WelcomeTwo";
    import About from "~/components/HomeOne/About";
    import Service from "~/components/HomeOne/Service";
    import Quote from "~/components/HomeOne/Quote";
    import Pricing from "~/components/HomeOne/Pricing";
    import Choose from "~/components/HomeOne/Choose";
    import Project from "~/components/HomeOne/Project";
    import Counter from "~/components/HomeOne/Counter";
    import Blog from "~/components/HomeOne/Blog";
    import Footer from "~/components/HomeOne/Footer";
    import Client from "~/components/HomeOne/Client";

    export default {
        name: "index-2",
      components: {

        Client,
        Footer,
        Blog,
        Counter,
        Project,
        Choose,
        Pricing,
        Quote,
        Service,
        About,
        WelcomeTwo,
        MainBanner,
        HeaderOne
        },
      head(){
        return{
          title: 'Home 2 | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>

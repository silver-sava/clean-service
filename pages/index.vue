<template>
  <div>
    <HeaderOne />
    <SliderOne />
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


import Project from "~/components/HomeOne/Project";
import HeaderOne from "~/components/HomeOne/HeaderOne";
import SliderOne from "~/components/HomeOne/SliderOne";
import Welcome from "~/components/HomeOne/Welcome";
import About from "~/components/HomeOne/About";
import Service from "~/components/HomeOne/Service";
import Quote from "~/components/HomeOne/Quote";
import Pricing from "~/components/HomeOne/Pricing";
import Choose from "~/components/HomeOne/Choose";
import Counter from "~/components/HomeOne/Counter";
import Blog from "~/components/HomeOne/Blog";
import Footer from "~/components/HomeOne/Footer";
import Cta from "~/components/HomeOne/Cta";
import Client from "~/components/HomeOne/Client";
export default {
  components: {
    Client,
    Cta,
    Footer,
    Blog,
    Counter,
    Choose,
    Pricing,
    Quote,
    Service,
    About,
    Welcome,
    SliderOne,
    HeaderOne,
    Project
  },
  head(){
    return{
      title: 'Home 1 | Clean Service'
    }
  },
}
</script>

<style>

</style>

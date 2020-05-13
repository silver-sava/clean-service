<template>
    <div>
      <HeaderOne />
      <PageBanner page-title="Contact us" banner-title="Contact" />
      <ContactDetails />
      <Map />
      <Footer />

    </div>
</template>

<script>
    import HeaderOne from "~/components/HomeOne/HeaderOne";
    import PageBanner from "~/components/Pages/PageBanner";
    import ContactDetails from "~/components/Pages/ContactDetails";
    import Map from "~/components/Pages/Map";
    import Footer from "~/components/HomeOne/Footer";
    export default {
        name: "contact",
      components: {
        Footer,
        Map,
        ContactDetails,
        PageBanner,
          HeaderOne
        },
      head(){
        return{
          title: 'Contact Us | Clean Service'
        }
      },
    }
</script>

<style scoped>

</style>
